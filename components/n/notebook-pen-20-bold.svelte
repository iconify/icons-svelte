<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g29p-d96q.css';
import '../../css/y/ym1dumb8f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="g29p-d96q"/><path class="ym1dumb8f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:notebook-pen-20-bold" {...props}></Icon>
