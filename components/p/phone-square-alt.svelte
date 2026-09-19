<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mfxmpcb8r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="mfxmpcb8r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:phone-square-alt" {...props}></Icon>
