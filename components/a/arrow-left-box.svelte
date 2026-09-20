<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j031vob3m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="j031vob3m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:arrow-left-box" {...props}></Icon>
