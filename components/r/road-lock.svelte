<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2sxe262x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="e2sxe262x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:road-lock" {...props}></Icon>
