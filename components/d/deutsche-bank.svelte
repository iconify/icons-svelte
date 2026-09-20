<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/unt8ljbcp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="unt8ljbcp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:deutsche-bank" {...props}></Icon>
