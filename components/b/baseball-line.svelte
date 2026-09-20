<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fvc2zcc1y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fvc2zcc1y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:baseball-line" {...props}></Icon>
