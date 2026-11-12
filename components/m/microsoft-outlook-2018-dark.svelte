<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lljgh4k1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="lljgh4k1v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:microsoft-outlook-2018-dark" {...props}></Icon>
