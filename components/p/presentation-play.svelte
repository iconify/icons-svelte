<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ru8xkse7f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ru8xkse7f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi-light:presentation-play" {...props}></Icon>
