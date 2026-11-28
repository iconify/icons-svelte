<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vw64u_b5h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="primary vw64u_b5h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:goal-duotone" {...props}></Icon>
