<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u_q4f9j6s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u_q4f9j6s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chevron-left-circle-filled" {...props}></Icon>
