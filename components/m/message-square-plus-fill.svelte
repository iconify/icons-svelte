<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bgvzp1bfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bgvzp1bfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:message-square-plus-fill" {...props}></Icon>
