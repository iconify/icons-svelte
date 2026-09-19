<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jpeaxcgkh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":496,"height":512};
const content = `<path class="jpeaxcgkh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:laugh-beam" {...props}></Icon>
