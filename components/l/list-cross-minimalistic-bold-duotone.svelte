<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b_yo8lb1d.css';
import '../../css/b/bktm07box.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="b_yo8lb1d"/><path class="bktm07box"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-cross-minimalistic-bold-duotone" {...props}></Icon>
