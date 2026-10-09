<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fnl2ysb4i.css';
import '../../css/x/xe8w9nb7g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fnl2ysb4i"/><path class="xe8w9nb7g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oscilloscope-20" {...props}></Icon>
