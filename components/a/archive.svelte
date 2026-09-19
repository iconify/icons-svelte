<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eyib19brx.css';
import '../../css/z/z477j3bdr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="eyib19brx"/><rect class="z477j3bdr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:archive" {...props}></Icon>
