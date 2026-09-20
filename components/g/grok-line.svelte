<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yoe6gv-um.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="yoe6gv-um"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:grok-line" {...props}></Icon>
