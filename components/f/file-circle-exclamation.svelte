<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oze8g3fll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="oze8g3fll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-circle-exclamation" {...props}></Icon>
