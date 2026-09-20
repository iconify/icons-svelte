<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f019l13qh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="f019l13qh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:bike" {...props}></Icon>
