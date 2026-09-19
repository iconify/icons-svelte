<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nq8dorxuf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nq8dorxuf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:keyframe-solid" {...props}></Icon>
