<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bwkmj8bsf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":384,"height":384};
const content = `<path class="bwkmj8bsf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zmdi:format-align-left" {...props}></Icon>
