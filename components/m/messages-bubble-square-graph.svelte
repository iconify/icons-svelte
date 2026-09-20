<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m643enbfo.css';
import '../../css/x/xd0tx35ws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m643enbfo"/><path class="xd0tx35ws"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand:messages-bubble-square-graph" {...props}></Icon>
