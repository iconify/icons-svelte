<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9pxw5fcl.css';
import '../../css/a/afvukzbcr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="e9pxw5fcl"/><path class="afvukzbcr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-download" {...props}></Icon>
