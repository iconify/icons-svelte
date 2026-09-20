<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mpdecacrv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mpdecacrv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:papermerge-dark" {...props}></Icon>
