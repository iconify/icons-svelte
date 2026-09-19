<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uzu4i-beq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uzu4i-beq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-ease-in" {...props}></Icon>
