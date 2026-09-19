<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jg5d1vbgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="jg5d1vbgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:file-circle-check" {...props}></Icon>
