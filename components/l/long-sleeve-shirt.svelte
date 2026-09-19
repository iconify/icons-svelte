<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/p/p-2b63b8i.css';
import '../../css/q/qnpqtcbjn.css';
import '../../css/j/jxwumcbuv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="p-2b63b8i"/><path class="qnpqtcbjn"/><path class="jxwumcbuv"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:long-sleeve-shirt" {...props}></Icon>
