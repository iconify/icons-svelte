<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fo1y8cbed.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="fo1y8cbed"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:arrow-right" {...props}></Icon>
