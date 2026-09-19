<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dnitxibej.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="dnitxibej"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-hold-linear-in" {...props}></Icon>
