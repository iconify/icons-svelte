<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddgx_yb3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddgx_yb3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:calendar-x2" {...props}></Icon>
