<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r57brub0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="r57brub0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:diskio" {...props}></Icon>
