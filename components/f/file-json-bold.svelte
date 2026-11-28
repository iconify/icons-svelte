<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k-v-bsb3t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="k-v-bsb3t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pullo:file-json-bold" {...props}></Icon>
