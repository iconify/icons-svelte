<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qxxuu8u_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qxxuu8u_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:folder-delete-line" {...props}></Icon>
