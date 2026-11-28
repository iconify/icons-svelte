<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kohl8lpdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="kohl8lpdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:olive-bold" {...props}></Icon>
