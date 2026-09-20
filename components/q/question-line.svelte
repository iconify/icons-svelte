<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp1_bxbav.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gp1_bxbav"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:question-line" {...props}></Icon>
