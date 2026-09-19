<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfn-b0b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="gfn-b0b7a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-brands:cc-mastercard" {...props}></Icon>
