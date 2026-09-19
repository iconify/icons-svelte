<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t1bvobxmo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="t1bvobxmo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icons8:hdd" {...props}></Icon>
