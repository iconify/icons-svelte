<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h921llb8w.css';
import '../../css/a/ausrfdcxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="h921llb8w"/><path class="ausrfdcxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charging-schedule-20-bold" {...props}></Icon>
