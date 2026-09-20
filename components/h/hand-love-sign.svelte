<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g__luxdwi.css';
import '../../css/v/vn0firbgu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="g__luxdwi"/><path class="vn0firbgu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-pixel:hand-love-sign" {...props}></Icon>
