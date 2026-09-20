<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mioqd3brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mioqd3brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:people-wearing-traditional-festive-latin-clothes" {...props}></Icon>
