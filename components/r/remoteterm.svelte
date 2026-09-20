<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jedolt31x.css';
import '../../css/w/wdqxtccbr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="jedolt31x"/><path class="wdqxtccbr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:remoteterm" {...props}></Icon>
