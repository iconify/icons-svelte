<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i--swg0uk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="i--swg0uk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:phone-square" {...props}></Icon>
