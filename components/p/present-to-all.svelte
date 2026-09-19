<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/du0py_b1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":472,"height":384};
const content = `<path class="du0py_b1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:present-to-all" {...props}></Icon>
