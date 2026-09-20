<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn6bgob1r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xn6bgob1r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:ad-choices" {...props}></Icon>
