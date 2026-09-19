<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/szrmdj49d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="szrmdj49d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:reading-glasses" {...props}></Icon>
