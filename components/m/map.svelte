<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/flugi-q2m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="flugi-q2m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="guidance:map" {...props}></Icon>
