<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gby97qwzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="gby97qwzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:home" {...props}></Icon>
