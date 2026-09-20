<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dr507ebah.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="dr507ebah"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:half-2" {...props}></Icon>
