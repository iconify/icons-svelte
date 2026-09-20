<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d99mpp4pu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="d99mpp4pu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:plus-circled" {...props}></Icon>
