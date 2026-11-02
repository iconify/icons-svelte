<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/txxypwbka.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="txxypwbka"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-big-up-dash-fill" {...props}></Icon>
