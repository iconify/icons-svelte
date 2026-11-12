<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gfbu4nbcu.css';
import '../../css/z/z6m2ovbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="gfbu4nbcu"/><path class="z6m2ovbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:alist" {...props}></Icon>
