<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bvevkhbsd.css';
import '../../css/f/fnx5s2bwf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bvevkhbsd"/><path class="fnx5s2bwf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:color-palette-sample-2" {...props}></Icon>
