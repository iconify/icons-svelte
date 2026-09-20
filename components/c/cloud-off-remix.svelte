<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zk_c1n3dh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="zk_c1n3dh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp:cloud-off-remix" {...props}></Icon>
