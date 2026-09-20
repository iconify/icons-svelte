<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/a/az8dcqgmq.css';
import '../../css/g/gcwqm4-4k.css';
import '../../css/x/xgtgfnecr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="az8dcqgmq"/><path class="gcwqm4-4k"/><path class="xgtgfnecr"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:box-add" {...props}></Icon>
