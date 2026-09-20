<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa27qpbce.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa27qpbce"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:explicit-filled" {...props}></Icon>
