<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zc0x3cccn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="zc0x3cccn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uil:behance" {...props}></Icon>
