<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p_fudbcsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p_fudbcsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:comment-account" {...props}></Icon>
