<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u30ldabiv.css';
import '../../css/m/mydhkgbks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="u30ldabiv"/><path class="mydhkgbks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:casino" {...props}></Icon>
