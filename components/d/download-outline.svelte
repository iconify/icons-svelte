<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lq84p-btl.css';
import '../../css/z/zurn3powf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="lq84p-btl"/><path class="zurn3powf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="basil:download-outline" {...props}></Icon>
