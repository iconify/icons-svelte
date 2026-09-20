<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m2rwiks3i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="m2rwiks3i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:interpreter" {...props}></Icon>
