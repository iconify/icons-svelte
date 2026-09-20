<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dpok98bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="dpok98bjd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:file-invoice-dollar" {...props}></Icon>
