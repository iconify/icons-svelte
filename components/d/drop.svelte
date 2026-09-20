<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tfpfexb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="tfpfexb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:drop" {...props}></Icon>
