<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ts4y51wse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="ts4y51wse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-xml-bold" {...props}></Icon>
