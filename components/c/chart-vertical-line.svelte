<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hw-_xjzoh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hw-_xjzoh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chart-vertical-line" {...props}></Icon>
