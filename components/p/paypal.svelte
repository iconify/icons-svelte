<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xl25jjb1d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="xl25jjb1d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bi:paypal" {...props}></Icon>
