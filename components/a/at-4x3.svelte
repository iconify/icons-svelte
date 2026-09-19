<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v18c9fbau.css';
import '../../css/f/f_vjhhbhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":480};
const content = `<path class="v18c9fbau"/><path class="f_vjhhbhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:at-4x3" {...props}></Icon>
