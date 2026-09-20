<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qs8thns5w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qs8thns5w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:photoprism-light" {...props}></Icon>
