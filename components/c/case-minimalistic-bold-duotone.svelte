<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ydbsjp0mn.css';
import '../../css/u/uv9075bbf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ydbsjp0mn"/><path class="uv9075bbf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:case-minimalistic-bold-duotone" {...props}></Icon>
