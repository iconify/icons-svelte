<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/de0b7s82y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="de0b7s82y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:comma" {...props}></Icon>
