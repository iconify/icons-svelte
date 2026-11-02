<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rqtmb4byj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="rqtmb4byj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:column-line" {...props}></Icon>
