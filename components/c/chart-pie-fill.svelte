<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xp5p-qjme.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="xp5p-qjme"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-pie-fill" {...props}></Icon>
