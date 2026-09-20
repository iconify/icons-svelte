<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r63o7bckj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="r63o7bckj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:heimdall" {...props}></Icon>
