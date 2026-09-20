<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lryz7mrcd.css';
import '../../css/r/rcmt1r3hl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lryz7mrcd"/><path class="rcmt1r3hl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:healthchecks" {...props}></Icon>
