<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/ryrhgi3ds.css';
import '../../css/x/x43m2tg3u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ryrhgi3ds"/><path class="x43m2tg3u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:file-cog-filled" {...props}></Icon>
