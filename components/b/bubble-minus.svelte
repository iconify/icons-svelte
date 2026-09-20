<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vx0j4pwwu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vx0j4pwwu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:bubble-minus" {...props}></Icon>
