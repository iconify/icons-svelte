<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w-h-79ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="w-h-79ber"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hospital-alt" {...props}></Icon>
