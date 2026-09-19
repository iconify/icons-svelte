<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oqs4gbbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":344,"height":432};
const content = `<path class="oqs4gbbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:rotate-right" {...props}></Icon>
