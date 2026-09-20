<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/exvj5hvyn.css';
import '../../css/s/sdgx1tzay.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="exvj5hvyn"/><path class="sdgx1tzay"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:audiodeck" {...props}></Icon>
