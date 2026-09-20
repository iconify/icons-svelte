<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/ke0_784jc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="ke0_784jc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:corner-top-left" {...props}></Icon>
