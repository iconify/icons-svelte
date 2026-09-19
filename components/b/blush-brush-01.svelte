<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3vv6gbmu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v3vv6gbmu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:blush-brush-01" {...props}></Icon>
