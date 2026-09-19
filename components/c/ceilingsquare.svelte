<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fy8fiyi9z.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fy8fiyi9z"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceilingsquare" {...props}></Icon>
