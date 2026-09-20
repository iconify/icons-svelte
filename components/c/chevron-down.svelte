<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e2sr5ccik.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="e2sr5ccik"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:chevron-down" {...props}></Icon>
