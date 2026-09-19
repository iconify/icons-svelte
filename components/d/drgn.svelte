<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d357irbtg.css';
import '../../css/t/tuels9bhh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="d357irbtg"/><path class="tuels9bhh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cryptocurrency:drgn" {...props}></Icon>
