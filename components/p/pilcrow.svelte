<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iq15uw1-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path clip-rule="evenodd" class="iq15uw1-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:pilcrow" {...props}></Icon>
