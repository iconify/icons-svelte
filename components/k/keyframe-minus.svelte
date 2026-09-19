<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ssj5qzlxm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ssj5qzlxm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconoir:keyframe-minus" {...props}></Icon>
