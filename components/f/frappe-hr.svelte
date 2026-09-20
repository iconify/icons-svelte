<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nevv_l36w.css';
import '../../css/g/gtg8rbctr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="nevv_l36w"/><path class="gtg8rbctr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:frappe-hr" {...props}></Icon>
