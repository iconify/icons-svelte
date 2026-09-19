<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmpj2ppka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":640};
const content = `<path class="pmpj2ppka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa7-solid:chevron-up" {...props}></Icon>
