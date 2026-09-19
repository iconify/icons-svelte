<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ebmm8_bcf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="ebmm8_bcf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-solid:mitsubishi" {...props}></Icon>
