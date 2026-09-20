<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yn9zjzj1e.css';
import '../../css/m/m52u-s6oe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yn9zjzj1e"/><path class="m52u-s6oe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:hammer-editor" {...props}></Icon>
