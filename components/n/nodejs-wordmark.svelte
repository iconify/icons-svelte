<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jk4mrjtlq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jk4mrjtlq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon-plain:nodejs-wordmark" {...props}></Icon>
