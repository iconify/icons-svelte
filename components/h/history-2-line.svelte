<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dg7dkbyqh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dg7dkbyqh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:history-2-line" {...props}></Icon>
