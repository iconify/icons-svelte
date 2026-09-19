<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oasq28blt.css';
import '../../css/d/dfc4wub2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="oasq28blt"/><path class="dfc4wub2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-calendar-plus" {...props}></Icon>
