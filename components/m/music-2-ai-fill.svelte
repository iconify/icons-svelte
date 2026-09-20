<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t3_301tyu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="t3_301tyu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:music-2-ai-fill" {...props}></Icon>
