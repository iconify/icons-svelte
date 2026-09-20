<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zx89iwb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="zx89iwb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:drag-handle-dots-2" {...props}></Icon>
