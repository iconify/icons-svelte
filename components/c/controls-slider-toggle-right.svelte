<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mvzt0qx4o.css';
import '../../css/u/uem9-5err.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mvzt0qx4o"/><path class="uem9-5err"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:controls-slider-toggle-right" {...props}></Icon>
