<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z-st6acvu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="z-st6acvu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-face-look-up-solid" {...props}></Icon>
