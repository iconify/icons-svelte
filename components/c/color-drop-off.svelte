<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pmf64gbbe.css';
import '../../css/f/f-3byccfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="pmf64gbbe"/><path class="f-3byccfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:color-drop-off" {...props}></Icon>
