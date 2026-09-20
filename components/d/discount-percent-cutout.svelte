<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isz0lobmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="isz0lobmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:discount-percent-cutout" {...props}></Icon>
