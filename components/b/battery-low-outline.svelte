<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wnqh4sixl.css';
import '../../css/n/n2noceb1n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wnqh4sixl"/><path clip-rule="evenodd" class="n2noceb1n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:battery-low-outline" {...props}></Icon>
