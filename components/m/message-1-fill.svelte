<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/ti_gfql_o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ti_gfql_o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-1-fill" {...props}></Icon>
