<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/yhp8qcbwr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="yhp8qcbwr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:baseball" {...props}></Icon>
