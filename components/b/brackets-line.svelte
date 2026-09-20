<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x7rd5pbsu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x7rd5pbsu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:brackets-line" {...props}></Icon>
