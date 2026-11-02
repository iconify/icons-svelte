<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g_go7u7sv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="g_go7u7sv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:refresh-3-fill" {...props}></Icon>
