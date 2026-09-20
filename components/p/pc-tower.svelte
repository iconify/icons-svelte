<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h3ge_6bdy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="h3ge_6bdy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:pc-tower" {...props}></Icon>
