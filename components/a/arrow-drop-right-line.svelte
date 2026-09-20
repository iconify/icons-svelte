<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hoit-5aey.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hoit-5aey"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:arrow-drop-right-line" {...props}></Icon>
