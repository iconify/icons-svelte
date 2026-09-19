<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jiqsblbdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="jiqsblbdi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:hard-hat" {...props}></Icon>
