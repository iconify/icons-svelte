<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_u-jrb4g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_u-jrb4g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:calendar-check" {...props}></Icon>
