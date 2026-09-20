<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zz6lu0z5m.css';
import '../../css/l/lfanpcblh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<circle class="zz6lu0z5m"/><path class="lfanpcblh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:loading-3-line" {...props}></Icon>
