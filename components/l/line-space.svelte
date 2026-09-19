<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rkj1c9jdu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rkj1c9jdu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:line-space" {...props}></Icon>
