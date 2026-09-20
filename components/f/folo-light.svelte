<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qc7jjcb-e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qc7jjcb-e"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:folo-light" {...props}></Icon>
