<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/g/gryrq_gjn.css';
import '../../css/l/l-jt8nbfd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="gryrq_gjn"/><path class="l-jt8nbfd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="proicons:folder-multiple" {...props}></Icon>
