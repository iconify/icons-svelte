<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp2nw3bpc.css';
import '../../css/k/k-8iobcst.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bp2nw3bpc"/><path class="k-8iobcst"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:bar-chart-sharp" {...props}></Icon>
