<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/e9med6bsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="e9med6bsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pepicons-pencil:grab-handle" {...props}></Icon>
