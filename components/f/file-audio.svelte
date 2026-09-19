<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jzh9jbtll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="jzh9jbtll"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:file-audio" {...props}></Icon>
