<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gu_4dpbmi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1200,"height":1200};
const content = `<path class="gu_4dpbmi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="el:bold" {...props}></Icon>
