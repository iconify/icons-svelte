<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vtrligblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vtrligblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bowling-outline" {...props}></Icon>
