<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp8b6cmyn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="pp8b6cmyn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="raphael:play" {...props}></Icon>
