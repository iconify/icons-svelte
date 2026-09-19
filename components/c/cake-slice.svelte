<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bnef_pb8w.css';
import '../../css/n/n2wyxqbbe.css';
import '../../css/f/f6r1adbsy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="bnef_pb8w"/><path class="n2wyxqbbe"/><path class="f6r1adbsy"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cake-slice" {...props}></Icon>
