<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nch3szbem.css';
import '../../css/d/d6mnshidp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="nch3szbem"/><path class="d6mnshidp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:ibm-watson-query" {...props}></Icon>
