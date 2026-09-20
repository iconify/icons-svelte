<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kjcq1f4bc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="kjcq1f4bc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:linguacafe-light" {...props}></Icon>
