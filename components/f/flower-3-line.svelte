<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gduepcbqm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gduepcbqm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:flower-3-line" {...props}></Icon>
