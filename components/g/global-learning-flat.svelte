<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/d/do_u7wljd.css';
import '../../css/f/f50bkxkxz.css';
import '../../css/f/frprfzvzu.css';
import '../../css/l/lld3lbcdl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="do_u7wljd"/><path class="f50bkxkxz"/><path class="frprfzvzu"/><path class="lld3lbcdl"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:global-learning-flat" {...props}></Icon>
