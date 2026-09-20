<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f8s6rvbsh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="f8s6rvbsh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:poker-hearts-fill" {...props}></Icon>
