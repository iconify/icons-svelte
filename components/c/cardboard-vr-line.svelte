<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xdw6qmbbg.css';
import '../../css/k/kwyvscbyk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="xdw6qmbbg"/><path class="kwyvscbyk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:cardboard-vr-line" {...props}></Icon>
