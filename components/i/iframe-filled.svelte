<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs9d7db8a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="vs9d7db8a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:iframe-filled" {...props}></Icon>
