<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srpjfu9ek.css';
import '../../css/f/f1fczmbyr.css';
import '../../css/g/g6145_v8p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="srpjfu9ek"/><path class="f1fczmbyr"/><path class="g6145_v8p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dumbbell-20" {...props}></Icon>
