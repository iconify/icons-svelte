<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/myi2hfncf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="myi2hfncf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:pin-bottom" {...props}></Icon>
