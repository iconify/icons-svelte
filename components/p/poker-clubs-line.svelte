<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_e483b4v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_e483b4v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:poker-clubs-line" {...props}></Icon>
