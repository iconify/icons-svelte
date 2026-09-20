<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v4597xbuu.css';
import '../../css/x/xrgvwubzt.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="v4597xbuu"/><path class="xrgvwubzt"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:heavy-rainstorm-fill" {...props}></Icon>
