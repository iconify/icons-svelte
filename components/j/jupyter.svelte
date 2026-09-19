<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y9ayah9kg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":376,"height":512};
const content = `<path class="y9ayah9kg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="file-icons:jupyter" {...props}></Icon>
