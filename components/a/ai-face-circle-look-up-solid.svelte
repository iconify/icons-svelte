<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w5bja3brp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w5bja3brp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:ai-face-circle-look-up-solid" {...props}></Icon>
