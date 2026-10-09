<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ofts-6g4o.css';
import '../../css/n/n0dt_tw8k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ofts-6g4o"/><path class="n0dt_tw8k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:panel-top-20" {...props}></Icon>
