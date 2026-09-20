<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pffnfbbjn.css';
import '../../css/m/mcl56li3l.css';
import '../../css/n/nadh9-zvh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="pffnfbbjn"/><path class="mcl56li3l"/><path class="nadh9-zvh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="material-icon-theme:folder-buildkite-open" {...props}></Icon>
