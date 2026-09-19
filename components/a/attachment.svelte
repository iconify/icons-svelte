<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i66pb1b_d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i66pb1b_d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:attachment" {...props}></Icon>
