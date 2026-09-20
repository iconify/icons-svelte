<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/lt79-dbim.css';
import '../../css/y/ywprslb-b.css';
import '../../css/d/dup_gbchp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="lt79-dbim"/><path class="ywprslb-b"/><path clip-rule="evenodd" class="dup_gbchp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:globe2-filled" {...props}></Icon>
