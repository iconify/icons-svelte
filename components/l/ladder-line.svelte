<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xd452hbro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xd452hbro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:ladder-line" {...props}></Icon>
