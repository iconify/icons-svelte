<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f0rp55rgj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f0rp55rgj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:border-right-plus" {...props}></Icon>
