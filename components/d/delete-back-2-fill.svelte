<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wgq8g5bls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wgq8g5bls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ri:delete-back-2-fill" {...props}></Icon>
