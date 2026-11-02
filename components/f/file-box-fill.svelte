<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ilmcf-bwl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ilmcf-bwl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:file-box-fill" {...props}></Icon>
