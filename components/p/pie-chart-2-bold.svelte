<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbf_yzbjl.css';
import '../../css/p/p3f1qdw5i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xbf_yzbjl"/><path class="p3f1qdw5i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:pie-chart-2-bold" {...props}></Icon>
