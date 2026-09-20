<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zr-5-vblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zr-5-vblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:paperplane-duotone" {...props}></Icon>
