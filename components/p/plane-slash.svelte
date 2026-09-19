<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wruaatbpy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="wruaatbpy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:plane-slash" {...props}></Icon>
