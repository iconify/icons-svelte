<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mav6eubkl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mav6eubkl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:call-calling-filled" {...props}></Icon>
