<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yqfk_pb6e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="yqfk_pb6e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:border-width" {...props}></Icon>
