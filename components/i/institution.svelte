<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcm2xebvr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qcm2xebvr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gridicons:institution" {...props}></Icon>
