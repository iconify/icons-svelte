<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jviohsbmh.css';
import '../../css/h/he3kxyb_v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="jviohsbmh"/><path class="he3kxyb_v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lock-48-bold" {...props}></Icon>
