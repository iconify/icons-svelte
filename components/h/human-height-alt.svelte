<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ic0iq61gn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ic0iq61gn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="pixelarticons:human-height-alt" {...props}></Icon>
