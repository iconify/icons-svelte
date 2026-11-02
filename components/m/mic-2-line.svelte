<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wb4qxybou.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wb4qxybou"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:mic-2-line" {...props}></Icon>
