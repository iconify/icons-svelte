<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_64j2bck.css';
import '../../css/a/ao9inwbnl.css';
import '../../css/z/zduyjj29s.css';
import '../../css/m/mtc92wbsn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j_64j2bck"/><path class="ao9inwbnl"/><path class="zduyjj29s"/><path class="mtc92wbsn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:peertube" {...props}></Icon>
