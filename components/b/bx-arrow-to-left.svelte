<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/awn-39bfj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="awn-39bfj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bx-arrow-to-left" {...props}></Icon>
