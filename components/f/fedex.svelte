<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/f53r9-bns.css';
import '../../css/b/bge442bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="f53r9-bns"/><path class="bge442bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:fedex" {...props}></Icon>
