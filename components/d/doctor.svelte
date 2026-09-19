<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4zn6vxvd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="r4zn6vxvd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:doctor" {...props}></Icon>
