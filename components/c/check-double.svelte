<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/trq7glk2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="trq7glk2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:check-double" {...props}></Icon>
