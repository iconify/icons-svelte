<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/b1nge0boq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="b1nge0boq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:hand-finger-line" {...props}></Icon>
