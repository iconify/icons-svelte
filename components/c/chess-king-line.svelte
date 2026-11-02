<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/uapnf89jn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="uapnf89jn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:chess-king-line" {...props}></Icon>
