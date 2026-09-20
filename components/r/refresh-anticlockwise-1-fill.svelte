<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/ws_650b2o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ws_650b2o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-anticlockwise-1-fill" {...props}></Icon>
