<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lrcd60buq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lrcd60buq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:list-indent-decrease-line" {...props}></Icon>
