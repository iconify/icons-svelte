<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p8wgcabdc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p8wgcabdc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lineicons:ios" {...props}></Icon>
