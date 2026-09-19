<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k4b5l8sta.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="k4b5l8sta"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-ease-out-filled" {...props}></Icon>
