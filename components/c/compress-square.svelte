<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vnovhgbzb.css';
import '../../css/f/f-uqiuafs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="vnovhgbzb"/><path class="f-uqiuafs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vaadin:compress-square" {...props}></Icon>
