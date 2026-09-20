<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8095eb2r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d8095eb2r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:document-fail" {...props}></Icon>
