<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtpeb-edw.css';
import '../../css/c/cjcrzte3y.css';
import '../../css/q/qmdhvtfgy.css';
import '../../css/b/bkb4aob9x.css';
import '../../css/h/h0homb0yl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="cjcrzte3y"/><path class="qmdhvtfgy"/></g><path class="bkb4aob9x"/><path class="h0homb0yl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:chevrons-right-left-bold-duotone" {...props}></Icon>
