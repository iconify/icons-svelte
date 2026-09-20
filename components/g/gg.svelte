<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m3v4-kb9g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="m3v4-kb9g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:gg" {...props}></Icon>
