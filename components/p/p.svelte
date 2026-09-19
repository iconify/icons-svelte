<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rmwd0txna.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="rmwd0txna"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:p" {...props}></Icon>
