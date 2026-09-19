<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ffp8ehbfy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ffp8ehbfy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:hand-sparkles" {...props}></Icon>
