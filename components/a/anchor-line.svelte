<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3he9mbmt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="t3he9mbmt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:anchor-line" {...props}></Icon>
