<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ihjy39qrh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="ihjy39qrh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:arrow-up-left-square" {...props}></Icon>
