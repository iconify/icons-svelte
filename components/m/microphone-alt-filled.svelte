<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jfmxxebmr.css';
import '../../css/j/j6k0-dpwv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jfmxxebmr"/><path class="j6k0-dpwv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:microphone-alt-filled" {...props}></Icon>
