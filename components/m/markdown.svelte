<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c3al6s0ue.css';
import '../../css/d/dys46yl0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="c3al6s0ue"/><path class="dys46yl0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:markdown" {...props}></Icon>
