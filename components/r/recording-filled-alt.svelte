<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jcay24bda.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jcay24bda"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:recording-filled-alt" {...props}></Icon>
