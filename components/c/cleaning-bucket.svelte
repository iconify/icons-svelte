<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/r/r74tqybkh.css';
import '../../css/w/w491debby.css';
import '../../css/b/b2z_ocb9i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="r74tqybkh"/><path class="w491debby"/><path class="b2z_ocb9i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:cleaning-bucket" {...props}></Icon>
