<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/ztme5hbiy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ztme5hbiy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:folder-music" {...props}></Icon>
