<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/k/k87mnbcsh.css';
import '../../css/s/s-m4y-b6j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="cuyn6tgcc"><path class="k87mnbcsh"/><path class="s-m4y-b6j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="rivet-icons:parking-solid" {...props}></Icon>
