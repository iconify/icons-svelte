<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xainp7b4f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xainp7b4f"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:red-packet-open-line" {...props}></Icon>
