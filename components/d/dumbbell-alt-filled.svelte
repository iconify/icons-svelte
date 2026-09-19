<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vq0e7yb2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vq0e7yb2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:dumbbell-alt-filled" {...props}></Icon>
