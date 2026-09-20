<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s3s8cpblg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="s3s8cpblg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-excel-2013-dark" {...props}></Icon>
