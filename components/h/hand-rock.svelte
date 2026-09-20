<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jmm3h1b-l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="jmm3h1b-l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="la:hand-rock" {...props}></Icon>
