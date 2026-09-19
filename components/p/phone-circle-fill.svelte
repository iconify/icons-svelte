<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofyn4sb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":56,"height":56};
const content = `<path class="ofyn4sb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="f7:phone-circle-fill" {...props}></Icon>
