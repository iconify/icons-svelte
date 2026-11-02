<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnqwgcbkf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lnqwgcbkf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:rainbow-fill" {...props}></Icon>
