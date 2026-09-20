<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d_nyb7jhv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d_nyb7jhv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:dice-1-line" {...props}></Icon>
