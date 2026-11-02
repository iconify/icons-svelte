<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r4f4hpsrl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="r4f4hpsrl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:document-3-line" {...props}></Icon>
