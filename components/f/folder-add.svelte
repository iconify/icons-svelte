<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wht68ernk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wht68ernk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-add" {...props}></Icon>
