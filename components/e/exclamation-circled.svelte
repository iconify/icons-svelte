<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rgu72z-ym.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rgu72z-ym"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:exclamation-circled" {...props}></Icon>
