<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vl-e23r9x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="vl-e23r9x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:modsquare" {...props}></Icon>
