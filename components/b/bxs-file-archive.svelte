<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xq8k_v7yc.css';
import '../../css/r/relvolb9u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xq8k_v7yc"/><path class="relvolb9u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-file-archive" {...props}></Icon>
