<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gg6xq2bvs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gg6xq2bvs"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:drop-line" {...props}></Icon>
