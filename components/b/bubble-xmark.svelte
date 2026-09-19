<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tuj89ebij.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tuj89ebij"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:bubble-xmark" {...props}></Icon>
