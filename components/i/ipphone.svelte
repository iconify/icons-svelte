<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wsu4ecc4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="wsu4ecc4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:ipphone" {...props}></Icon>
