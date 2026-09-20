<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/waf5nr0aw.css';
import '../../css/f/flc22bblw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="waf5nr0aw"/><path class="flc22bblw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:filesync" {...props}></Icon>
