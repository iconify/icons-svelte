<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjgr2hbwh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjgr2hbwh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rain-line" {...props}></Icon>
