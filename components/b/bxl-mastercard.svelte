<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/isx0-mbjk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="isx0-mbjk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxl-mastercard" {...props}></Icon>
