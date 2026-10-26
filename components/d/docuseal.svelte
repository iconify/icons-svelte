<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lfzmct09b.css';
import '../../css/x/xkn94gxsg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":180,"height":180};
const content = `<path class="lfzmct09b"/><circle class="xkn94gxsg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg:docuseal" {...props}></Icon>
