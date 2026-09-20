<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v-fw0acxe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v-fw0acxe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:pencil-3-ai-line" {...props}></Icon>
