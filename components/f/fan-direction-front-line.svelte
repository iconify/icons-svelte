<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s1h0yxuds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s1h0yxuds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:fan-direction-front-line" {...props}></Icon>
