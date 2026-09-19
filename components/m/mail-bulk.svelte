<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rtqi52c4n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":576,"height":512};
const content = `<path class="rtqi52c4n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa-solid:mail-bulk" {...props}></Icon>
