<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ro-gslbcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ro-gslbcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:internet-explorer" {...props}></Icon>
