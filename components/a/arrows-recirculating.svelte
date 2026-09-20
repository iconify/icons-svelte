<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft0qlnbsa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ft0qlnbsa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:arrows-recirculating" {...props}></Icon>
