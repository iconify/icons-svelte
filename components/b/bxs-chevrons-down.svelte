<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n185p7bwm.css';
import '../../css/i/iylza4btn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="n185p7bwm"/><path class="iylza4btn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-chevrons-down" {...props}></Icon>
