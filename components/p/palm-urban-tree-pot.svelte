<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x0y-h_16m.css';
import '../../css/k/ke0zg7b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="x0y-h_16m"/><path class="ke0zg7b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="roentgen:palm-urban-tree-pot" {...props}></Icon>
