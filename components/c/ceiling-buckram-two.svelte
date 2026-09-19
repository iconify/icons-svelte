<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lyz9kejrz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lyz9kejrz"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cbi:ceiling-buckram-two" {...props}></Icon>
