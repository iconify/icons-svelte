<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ci7_qzgce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ci7_qzgce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:cargobike-and-locked-lock-with-keyhole" {...props}></Icon>
