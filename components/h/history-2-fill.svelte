<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qeqir1bhu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qeqir1bhu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:history-2-fill" {...props}></Icon>
