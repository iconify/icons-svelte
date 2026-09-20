<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iikjkgxcq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="iikjkgxcq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mdi:image-off" {...props}></Icon>
