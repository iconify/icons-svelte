<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s2d0-mhrd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="s2d0-mhrd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:qnap-logo" {...props}></Icon>
