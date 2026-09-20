<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q82_asybb.css';
import '../../css/j/jz4z07ajo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="q82_asybb"/><path class="jz4z07ajo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:drawer-upload-bold" {...props}></Icon>
