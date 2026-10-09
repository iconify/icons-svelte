<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/itz70zb2a.css';
import '../../css/r/ry8p8oeqb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="itz70zb2a"/><path class="ry8p8oeqb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dining-20" {...props}></Icon>
