<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/llzqa-0gd.css';
import '../../css/w/wkau1rbrb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="llzqa-0gd"/><path class="wkau1rbrb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:document-lock" {...props}></Icon>
