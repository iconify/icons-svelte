<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pa8fp8b1o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pa8fp8b1o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uit:angle-double-down" {...props}></Icon>
