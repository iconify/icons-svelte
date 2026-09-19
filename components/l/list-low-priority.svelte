<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hi0f-zb-z.css';
import '../../css/j/jvrj_gb8g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hi0f-zb-z"/><path class="jvrj_gb8g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:list-low-priority" {...props}></Icon>
