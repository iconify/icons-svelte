<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9cj9y50u.css';
import '../../css/o/oy6hf0bjo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o9cj9y50u"/><path class="oy6hf0bjo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:loading-3-line" {...props}></Icon>
