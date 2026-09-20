<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvhs7gbxt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="mvhs7gbxt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:mask-on" {...props}></Icon>
