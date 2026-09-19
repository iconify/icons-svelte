<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/ot2aw6chb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="ot2aw6chb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-solid:bridge-circle-xmark" {...props}></Icon>
