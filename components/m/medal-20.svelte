<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/oa8cast3m.css';
import '../../css/q/qxzfcfqis.css';
import '../../css/p/p10chkbow.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="oa8cast3m"/><path class="qxzfcfqis"/><path class="p10chkbow"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:medal-20" {...props}></Icon>
