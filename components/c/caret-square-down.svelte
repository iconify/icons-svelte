<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6ulymbat.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="w6ulymbat"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:caret-square-down" {...props}></Icon>
