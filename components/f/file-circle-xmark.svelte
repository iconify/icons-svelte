<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r94-uy7iz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="r94-uy7iz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-circle-xmark" {...props}></Icon>
