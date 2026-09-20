<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rjd0kis-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="rjd0kis-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:mixer-vertical" {...props}></Icon>
