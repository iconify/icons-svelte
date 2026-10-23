<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d-4x6qhpb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d-4x6qhpb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:door-closed-locked" {...props}></Icon>
