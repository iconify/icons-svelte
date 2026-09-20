<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-8_6ui7s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="t-8_6ui7s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:move" {...props}></Icon>
