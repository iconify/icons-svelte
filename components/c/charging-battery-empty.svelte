<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hj2vn1_gs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hj2vn1_gs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:charging-battery-empty" {...props}></Icon>
