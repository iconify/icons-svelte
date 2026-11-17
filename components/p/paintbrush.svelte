<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xn5eo9bqs.css';
import '../../css/s/skzq3efbt.css';
import '../../css/p/p4ojfpbms.css';
import '../../css/b/bv8sd55gu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xn5eo9bqs"><path class="skzq3efbt"/><path class="p4ojfpbms"/><path class="bv8sd55gu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="matita:paintbrush" {...props}></Icon>
