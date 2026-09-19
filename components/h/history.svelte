<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s17-xn6bb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s17-xn6bb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="akar-icons:history" {...props}></Icon>
