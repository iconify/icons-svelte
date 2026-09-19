<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fu4qu4p3r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="fu4qu4p3r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:cloud" {...props}></Icon>
