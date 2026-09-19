<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t4omieb6b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t4omieb6b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:enlarge" {...props}></Icon>
