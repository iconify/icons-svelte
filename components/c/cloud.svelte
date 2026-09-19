<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dgriz_p_e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dgriz_p_e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:cloud" {...props}></Icon>
