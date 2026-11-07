<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/ss1pzwrkh.css';
import '../../css/z/zn22gsbin.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="ss1pzwrkh"/><path class="zn22gsbin"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:medal-star-circle-bold" {...props}></Icon>
