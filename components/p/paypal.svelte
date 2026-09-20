<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/js6l_obbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="js6l_obbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:paypal" {...props}></Icon>
