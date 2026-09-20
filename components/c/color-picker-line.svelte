<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/ejow65bjs.css';
import '../../css/q/qwigwhghd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="ejow65bjs"/><path class="qwigwhghd"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:color-picker-line" {...props}></Icon>
