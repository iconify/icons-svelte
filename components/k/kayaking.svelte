<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ugu5vab6m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ugu5vab6m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:kayaking" {...props}></Icon>
