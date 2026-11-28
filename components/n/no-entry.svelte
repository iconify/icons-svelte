<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qsdd16vxh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="qsdd16vxh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="noviair-light:no-entry" {...props}></Icon>
