<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q65t7t7ey.css';
import '../../css/i/iff33zhfm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="q65t7t7ey"/><path class="iff33zhfm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:rotate-ccw-20-bold" {...props}></Icon>
