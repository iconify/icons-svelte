<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zej5dm5-i.css';
import '../../css/a/abnnwxzhi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zej5dm5-i"/><path clip-rule="evenodd" class="abnnwxzhi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:download-bold-duotone" {...props}></Icon>
