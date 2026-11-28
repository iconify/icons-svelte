<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/axcrtbcwi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="axcrtbcwi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:backpack-check" {...props}></Icon>
