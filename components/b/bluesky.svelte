<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fsyi7db4m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fsyi7db4m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bluesky" {...props}></Icon>
