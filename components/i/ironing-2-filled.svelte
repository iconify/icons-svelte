<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i8c0xac2k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="i8c0xac2k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:ironing-2-filled" {...props}></Icon>
