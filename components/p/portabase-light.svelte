<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ln4zqubks.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="ln4zqubks"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:portabase-light" {...props}></Icon>
