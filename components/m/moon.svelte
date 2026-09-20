<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g-9vnkbuu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="g-9vnkbuu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:moon" {...props}></Icon>
