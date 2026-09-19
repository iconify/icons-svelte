<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/te04s0bgi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":666,"height":733};
const content = `<path class="te04s0bgi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:repeat" {...props}></Icon>
