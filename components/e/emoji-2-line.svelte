<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nbb6-l2kn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="nbb6-l2kn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:emoji-2-line" {...props}></Icon>
