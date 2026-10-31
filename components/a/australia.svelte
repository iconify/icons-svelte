<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yl8x224tx.css';
import '../../css/w/ww52sv46j.css';
import '../../css/n/nv4ztabcc.css';
import '../../css/o/o6rwwebbc.css';
import '../../css/u/ufzh-1jpi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":30,"height":24};
const content = `<path class="yl8x224tx"/><path class="ww52sv46j"/><path class="nv4ztabcc"/><path class="o6rwwebbc"/><path class="ufzh-1jpi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler-flags:australia" {...props}></Icon>
