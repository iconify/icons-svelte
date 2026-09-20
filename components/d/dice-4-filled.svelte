<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ycxdoji9k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ycxdoji9k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:dice-4-filled" {...props}></Icon>
