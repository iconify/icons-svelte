<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pu52i9kgw.css';
import '../../css/x/x4jxcf4cm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="pu52i9kgw"/><path class="x4jxcf4cm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:qatar" {...props}></Icon>
