<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j3gj7abse.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path class="j3gj7abse"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:politics-speech" {...props}></Icon>
