<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f_8j1tbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":768,"height":646};
const content = `<path class="f_8j1tbxn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ls:invert" {...props}></Icon>
