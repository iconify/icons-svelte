<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfyok6bld.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mfyok6bld"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:any-solvent-without-tetrachlorethylene" {...props}></Icon>
