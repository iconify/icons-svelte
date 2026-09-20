<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t522e0tcu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t522e0tcu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:font-italic" {...props}></Icon>
