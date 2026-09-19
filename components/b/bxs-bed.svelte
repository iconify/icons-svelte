<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dss77kb_x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dss77kb_x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-bed" {...props}></Icon>
