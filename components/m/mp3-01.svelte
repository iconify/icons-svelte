<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gczf5uo1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gczf5uo1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mp3-01" {...props}></Icon>
