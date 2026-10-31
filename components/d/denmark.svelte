<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k42v9bvgu.css';
import '../../css/z/z3o5mebhd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="k42v9bvgu"/><path class="z3o5mebhd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:denmark" {...props}></Icon>
