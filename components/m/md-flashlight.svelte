<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wf4aesbfn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wf4aesbfn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:md-flashlight" {...props}></Icon>
