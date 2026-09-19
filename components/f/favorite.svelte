<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oe555z8cp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1026,"height":962};
const content = `<path class="oe555z8cp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:favorite" {...props}></Icon>
