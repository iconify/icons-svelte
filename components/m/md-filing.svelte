<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w0uri6bcg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="w0uri6bcg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-filing" {...props}></Icon>
