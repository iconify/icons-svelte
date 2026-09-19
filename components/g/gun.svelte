<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ww5lr-bzr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="ww5lr-bzr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:gun" {...props}></Icon>
