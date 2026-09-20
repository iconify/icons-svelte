<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c0m45uarn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="c0m45uarn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:align-center-vertically" {...props}></Icon>
