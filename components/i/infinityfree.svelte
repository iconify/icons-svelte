<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xj1t25d3l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xj1t25d3l"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:infinityfree" {...props}></Icon>
