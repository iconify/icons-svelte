<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bj0ca7rqc.css';
import '../../css/i/ij9mepbyb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<circle class="bj0ca7rqc"/><path class="ij9mepbyb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:graphhopper" {...props}></Icon>
