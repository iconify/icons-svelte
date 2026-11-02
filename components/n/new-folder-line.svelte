<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tgbi-g60n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="tgbi-g60n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:new-folder-line" {...props}></Icon>
