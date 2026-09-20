<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz_zt233x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="vz_zt233x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:cue" {...props}></Icon>
