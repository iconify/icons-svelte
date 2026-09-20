<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/c22_dcbkt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="c22_dcbkt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:notebook3-filled" {...props}></Icon>
