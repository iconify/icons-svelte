<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp8rpxbui.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="xp8rpxbui"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:image" {...props}></Icon>
