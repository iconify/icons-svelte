<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zhavmnomc.css';
import '../../css/m/myhuogbnq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zhavmnomc"/><path class="myhuogbnq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:cpu-bold-duotone" {...props}></Icon>
