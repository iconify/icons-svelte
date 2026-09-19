<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wrhom2bqr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":704,"height":1024};
const content = `<path class="wrhom2bqr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:handdown" {...props}></Icon>
