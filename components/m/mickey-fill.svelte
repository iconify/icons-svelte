<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hfy1igbox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hfy1igbox"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:mickey-fill" {...props}></Icon>
