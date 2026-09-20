<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iir0f5bog.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":11,"height":11};
const content = `<path class="iir0f5bog"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="maki:city-11" {...props}></Icon>
