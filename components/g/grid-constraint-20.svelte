<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxafyvbuf.css';
import '../../css/t/t7uk038zd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wxafyvbuf"/><path class="t7uk038zd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:grid-constraint-20" {...props}></Icon>
