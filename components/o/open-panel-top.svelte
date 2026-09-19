<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/whnn-4bjf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="whnn-4bjf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:open-panel-top" {...props}></Icon>
