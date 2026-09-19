<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/smegf5bhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="smegf5bhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:copy" {...props}></Icon>
