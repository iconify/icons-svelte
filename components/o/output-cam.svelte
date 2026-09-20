<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8z3ufmty.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="p8z3ufmty"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:output-cam" {...props}></Icon>
