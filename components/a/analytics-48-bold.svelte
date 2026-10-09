<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oz0-7c0kb.css';
import '../../css/f/fpw9y5b6x.css';
import '../../css/h/hjih05f-k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="oz0-7c0kb"/><path class="fpw9y5b6x"/><path class="hjih05f-k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:analytics-48-bold" {...props}></Icon>
