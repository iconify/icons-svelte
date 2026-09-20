<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lvtef0brw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lvtef0brw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:controls-sliders-vertical" {...props}></Icon>
