<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bjlc6qbxc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bjlc6qbxc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:minus-circle-dash-fill" {...props}></Icon>
