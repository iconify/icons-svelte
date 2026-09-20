<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y2lkowdni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="y2lkowdni"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-excel-2018-dark" {...props}></Icon>
