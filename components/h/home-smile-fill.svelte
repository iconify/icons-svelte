<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/slxdrq1zo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="slxdrq1zo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:home-smile-fill" {...props}></Icon>
