<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wclb063ro.css';
import '../../css/l/lzqod34yu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wclb063ro"/><path class="lzqod34yu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:hard-drive" {...props}></Icon>
