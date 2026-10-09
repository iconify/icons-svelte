<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jkpulpb9y.css';
import '../../css/p/p1om3-m6g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="jkpulpb9y"/><path class="p1om3-m6g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:app-window-20-bold" {...props}></Icon>
