<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/p-2lfhb0x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="p-2lfhb0x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:redo3-filled" {...props}></Icon>
