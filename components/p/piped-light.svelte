<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f88f6cb-x.css';
import '../../css/a/a2th6qhaq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f88f6cb-x"/><path class="a2th6qhaq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:piped-light" {...props}></Icon>
