<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vb8udxb0c.css';
import '../../css/g/gxpq89blg.css';
import '../../css/m/mse88bcix.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vb8udxb0c"/><path clip-rule="evenodd" class="gxpq89blg"/><path class="mse88bcix"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:programming-flowchart" {...props}></Icon>
