<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/muo3kxbex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="muo3kxbex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bxl:paypal" {...props}></Icon>
