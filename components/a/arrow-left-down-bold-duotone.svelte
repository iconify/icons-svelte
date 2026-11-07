<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tm99dfc3e.css';
import '../../css/c/cvyd4hdhk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="tm99dfc3e"/><path class="cvyd4hdhk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:arrow-left-down-bold-duotone" {...props}></Icon>
