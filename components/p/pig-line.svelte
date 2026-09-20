<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qy2z1ezds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qy2z1ezds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pig-line" {...props}></Icon>
