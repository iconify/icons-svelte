<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vz8t8__qs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="vz8t8__qs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:cross-1" {...props}></Icon>
