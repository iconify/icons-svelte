<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hhb8c01ug.css';
import '../../css/r/rirt7bcol.css';
import '../../css/m/mzxbszjzr.css';
import '../../css/d/dmlxnibql.css';
import '../../css/r/ryby98ucd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hhb8c01ug"><path class="rirt7bcol"/><path class="mzxbszjzr"/><path class="dmlxnibql"/><path class="ryby98ucd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="catppuccin:postcss" {...props}></Icon>
