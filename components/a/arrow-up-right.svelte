<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c5xzettmq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c5xzettmq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:arrow-up-right" {...props}></Icon>
