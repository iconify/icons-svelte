<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pv2w0mb5e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="pv2w0mb5e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:font-size" {...props}></Icon>
