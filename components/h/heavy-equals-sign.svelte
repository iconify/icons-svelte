<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/murjelbxg.css';
import '../../css/y/y_31qtbyx.css';
import '../../css/x/xoiqtfx8i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":72,"height":72};
const content = `<path class="murjelbxg"/><path class="y_31qtbyx"/><path class="xoiqtfx8i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="openmoji:heavy-equals-sign" {...props}></Icon>
