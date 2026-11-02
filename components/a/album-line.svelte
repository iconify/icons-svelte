<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qem2vs-wc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qem2vs-wc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:album-line" {...props}></Icon>
