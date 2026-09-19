<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fbfztel_k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fbfztel_k"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:eject-filled" {...props}></Icon>
