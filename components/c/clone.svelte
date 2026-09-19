<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eq9sqgbrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eq9sqgbrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-regular:clone" {...props}></Icon>
