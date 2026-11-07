<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zenyhg4uf.css';
import '../../css/w/wljgqrbai.css';
import '../../css/s/suoyyrb8y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zenyhg4uf"/><path class="wljgqrbai"/><path class="suoyyrb8y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:crop-minimalistic-bold-duotone" {...props}></Icon>
