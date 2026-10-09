<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o9ls55b_f.css';
import '../../css/n/n0np7fbxk.css';
import '../../css/j/j1y330bee.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="o9ls55b_f"/><path class="n0np7fbxk"/><path class="j1y330bee"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:import-export-20" {...props}></Icon>
