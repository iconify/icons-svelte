<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddb602buy.css';
import '../../css/z/z84lzbbag.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ddb602buy"/><path class="z84lzbbag"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:refresh-bold-duotone" {...props}></Icon>
