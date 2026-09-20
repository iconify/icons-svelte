<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/euz42-bsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="euz42-bsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:multimedia-controls-loop-arrow" {...props}></Icon>
