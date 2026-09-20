<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wcllbexzj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="wcllbexzj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:caret-right" {...props}></Icon>
