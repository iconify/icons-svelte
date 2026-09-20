<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/srhk6lb1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="srhk6lb1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:quickwit-dark" {...props}></Icon>
