<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w86rhlbvt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":717,"height":646};
const content = `<path class="w86rhlbvt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:dashboard" {...props}></Icon>
