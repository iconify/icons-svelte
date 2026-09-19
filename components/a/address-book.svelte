<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwqc1t6co.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="iwqc1t6co"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:address-book" {...props}></Icon>
