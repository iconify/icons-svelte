<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fv-1j60oc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fv-1j60oc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrow-down" {...props}></Icon>
