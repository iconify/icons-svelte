<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuukbzbho.css';
import '../../css/x/xw75jrbbi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":64,"height":64};
const content = `<path class="vuukbzbho"/><path class="xw75jrbbi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:map" {...props}></Icon>
