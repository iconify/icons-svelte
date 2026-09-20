<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2bt4rt7h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="u2bt4rt7h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:numbers-fill" {...props}></Icon>
