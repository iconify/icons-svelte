<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qppggacgf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qppggacgf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:dimo" {...props}></Icon>
