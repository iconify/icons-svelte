<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/aqp1t41-r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="aqp1t41-r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:keyframe-align-center" {...props}></Icon>
