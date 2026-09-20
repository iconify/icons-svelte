<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fyw3bwjwo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fyw3bwjwo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:device-imac-filled" {...props}></Icon>
