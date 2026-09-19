<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uas6i0ufn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":256,"height":256};
const content = `<path class="uas6i0ufn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fad:drumpad" {...props}></Icon>
