<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hynv5rb0a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hynv5rb0a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:close-medium-line" {...props}></Icon>
