<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/en6999bcy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="en6999bcy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bugs" {...props}></Icon>
