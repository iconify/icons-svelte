<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cpye2rdex.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cpye2rdex"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:boots" {...props}></Icon>
