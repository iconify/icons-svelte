<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tzxk1obup.css';
import '../../css/w/wfs41yb4d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tzxk1obup"/><path class="wfs41yb4d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bookmark-plus" {...props}></Icon>
