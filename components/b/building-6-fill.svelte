<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf243ixuw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="wf243ixuw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:building-6-fill" {...props}></Icon>
