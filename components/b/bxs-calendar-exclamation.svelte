<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gd8l7cc2q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gd8l7cc2q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-calendar-exclamation" {...props}></Icon>
