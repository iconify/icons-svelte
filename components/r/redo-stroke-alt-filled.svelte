<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d8zrl8s0r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="d8zrl8s0r"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:redo-stroke-alt-filled" {...props}></Icon>
