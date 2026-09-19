<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/x467bpb8x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="x467bpb8x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:arrow-long-left" {...props}></Icon>
