<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zsw1rgb1l.css';
import '../../css/x/x3xddwbyo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="zsw1rgb1l"/><path class="x3xddwbyo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:distribution-board-20" {...props}></Icon>
