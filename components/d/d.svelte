<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jux0wcfxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jux0wcfxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:d" {...props}></Icon>
