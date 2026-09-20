<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x4nvk1g0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="x4nvk1g0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:color-wheel" {...props}></Icon>
