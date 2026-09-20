<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h96hfv_iy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="h96hfv_iy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="radix-icons:minus-circled" {...props}></Icon>
