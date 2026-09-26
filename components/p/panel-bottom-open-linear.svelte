<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/e/e6ihngbuj.css';
import '../../css/b/b2vvr6bvh.css';
import '../../css/n/n9h5_9byn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="e6ihngbuj"/><path class="b2vvr6bvh"/><path class="n9h5_9byn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:panel-bottom-open-linear" {...props}></Icon>
