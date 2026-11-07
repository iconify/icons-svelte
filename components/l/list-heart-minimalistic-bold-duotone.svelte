<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bmnoaub3f.css';
import '../../css/y/y4c08ncxf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="bmnoaub3f"/><path class="y4c08ncxf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-heart-minimalistic-bold-duotone" {...props}></Icon>
