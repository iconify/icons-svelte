<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jm3x06xxr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jm3x06xxr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:hololens" {...props}></Icon>
