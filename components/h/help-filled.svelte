<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fiqbokbbo.css';
import '../../css/j/j0ryq4_tz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="fiqbokbbo"/><path class="j0ryq4_tz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:help-filled" {...props}></Icon>
