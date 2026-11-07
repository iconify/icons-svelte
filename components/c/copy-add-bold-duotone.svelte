<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mtplmt03a.css';
import '../../css/p/p6laxfbun.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mtplmt03a"/><path clip-rule="evenodd" class="p6laxfbun"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:copy-add-bold-duotone" {...props}></Icon>
