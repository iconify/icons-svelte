<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_0_lnbrr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":448,"height":512};
const content = `<path class="w_0_lnbrr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:floppy-disk" {...props}></Icon>
