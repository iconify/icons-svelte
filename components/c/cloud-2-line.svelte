<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bnzy-i2jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bnzy-i2jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cloud-2-line" {...props}></Icon>
