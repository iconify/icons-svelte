<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d4d9q7zmc.css';
import '../../css/z/zto9ilb4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="d4d9q7zmc"/><path class="zto9ilb4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oil-20" {...props}></Icon>
