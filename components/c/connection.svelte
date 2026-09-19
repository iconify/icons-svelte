<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tc86c7rgn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":16};
const content = `<path class="tc86c7rgn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:connection" {...props}></Icon>
