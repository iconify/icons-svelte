<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mlu76z99o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="mlu76z99o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="mingcute:arrow-left-circle-line" {...props}></Icon>
