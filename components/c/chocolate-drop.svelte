<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p1i8aybke.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<path class="p1i8aybke"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pinhead:chocolate-drop" {...props}></Icon>
