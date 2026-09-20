<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/ah81sc2kd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ah81sc2kd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uiw:link" {...props}></Icon>
