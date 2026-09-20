<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hm5xk5b_g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hm5xk5b_g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:expand-height-line" {...props}></Icon>
