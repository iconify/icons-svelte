<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vs16rbccl.css';
import '../../css/t/t9suffddk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="vs16rbccl"/><path class="t9suffddk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:proxcenter" {...props}></Icon>
