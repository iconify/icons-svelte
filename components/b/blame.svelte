<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c8g3p2xah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="c8g3p2xah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:blame" {...props}></Icon>
