<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w6klmnb1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="w6klmnb1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:hand-heart-fill" {...props}></Icon>
