<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dqbdr3bwf.css';
import '../../css/l/lq302uv1z.css';
import '../../css/g/gsxsmjbdv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="dqbdr3bwf"/><path class="lq302uv1z"/><path class="gsxsmjbdv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:palm-tree-20-bold" {...props}></Icon>
