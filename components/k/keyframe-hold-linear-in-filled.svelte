<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y_j66ccof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y_j66ccof"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-hold-linear-in-filled" {...props}></Icon>
