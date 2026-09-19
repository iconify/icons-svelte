<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x3beakb9w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="x3beakb9w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-hold-ease-out" {...props}></Icon>
