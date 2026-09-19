<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/m1c0irbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="m1c0irbuv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:music-note-04" {...props}></Icon>
