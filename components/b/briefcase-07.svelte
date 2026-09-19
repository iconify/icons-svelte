<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vuw2p1vit.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vuw2p1vit"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:briefcase-07" {...props}></Icon>
