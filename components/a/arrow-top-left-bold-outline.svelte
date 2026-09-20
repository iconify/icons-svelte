<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uv2f2z9dj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uv2f2z9dj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-top-left-bold-outline" {...props}></Icon>
