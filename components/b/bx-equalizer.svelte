<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jv33s8bwk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jv33s8bwk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-equalizer" {...props}></Icon>
