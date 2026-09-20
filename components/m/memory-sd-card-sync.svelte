<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/l/l-emcpb2w.css';
import '../../css/w/wxfiv0ytx.css';
import '../../css/l/lelt0sbvz.css';
import '../../css/w/w5z-ygk9y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="l-emcpb2w"/><path class="wxfiv0ytx"/><path class="lelt0sbvz"/><path class="w5z-ygk9y"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-freehand-color:memory-sd-card-sync" {...props}></Icon>
