<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mubd4760u.css';
import '../../css/h/hfy0htikh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="mubd4760u"/><path class="hfy0htikh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:history-20-bold" {...props}></Icon>
