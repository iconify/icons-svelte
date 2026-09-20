<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cxil07bhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="cxil07bhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:bowling-ball" {...props}></Icon>
