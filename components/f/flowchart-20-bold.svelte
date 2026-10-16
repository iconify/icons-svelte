<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nyvh6kk2s.css';
import '../../css/j/jk43hwbxb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="nyvh6kk2s"/><path class="jk43hwbxb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:flowchart-20-bold" {...props}></Icon>
