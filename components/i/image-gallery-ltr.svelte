<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoz3r3bes.css';
import '../../css/y/ycqomi9-f.css';
import '../../css/v/vvstocchj.css';
import '../../css/z/z9gopggrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hoz3r3bes"/><path class="ycqomi9-f"/><path class="vvstocchj"/><circle class="z9gopggrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ooui:image-gallery-ltr" {...props}></Icon>
