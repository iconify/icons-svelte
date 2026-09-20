<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_5ziluza.css';
import '../../css/x/xi4gy0bjp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_5ziluza"/><path class="xi4gy0bjp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:homepod-line" {...props}></Icon>
