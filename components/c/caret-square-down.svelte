<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/a4p_33ayd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="a4p_33ayd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:caret-square-down" {...props}></Icon>
