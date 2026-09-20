<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufz89ibmb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ufz89ibmb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:face-mask" {...props}></Icon>
