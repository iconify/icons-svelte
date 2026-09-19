<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hb3q1erga.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1664};
const content = `<path class="hb3q1erga"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vs:neko-sleep" {...props}></Icon>
