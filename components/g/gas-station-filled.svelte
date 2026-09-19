<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kccx5mbrd.css';
import '../../css/c/cigvp3btk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="kccx5mbrd"/><path class="cigvp3btk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:gas-station-filled" {...props}></Icon>
