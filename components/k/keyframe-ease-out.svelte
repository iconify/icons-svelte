<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vgkbm7kca.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vgkbm7kca"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:keyframe-ease-out" {...props}></Icon>
