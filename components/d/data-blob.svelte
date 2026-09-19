<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ca5ecz53l.css';
import '../../css/r/rrrw2jbhj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ca5ecz53l"/><path class="rrrw2jbhj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:data-blob" {...props}></Icon>
