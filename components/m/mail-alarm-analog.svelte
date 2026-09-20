<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/warw91tyv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path clip-rule="evenodd" class="warw91tyv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ix:mail-alarm-analog" {...props}></Icon>
