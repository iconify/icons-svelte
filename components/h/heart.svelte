<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cidg1bb9e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="cidg1bb9e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:heart" {...props}></Icon>
