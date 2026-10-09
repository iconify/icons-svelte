<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l-h4xkbtz.css';
import '../../css/p/p1ofzbbnm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="l-h4xkbtz"/><path class="p1ofzbbnm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:jersey-20" {...props}></Icon>
