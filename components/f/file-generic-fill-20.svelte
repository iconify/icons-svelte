<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fgv34el5t.css';
import '../../css/n/nsl4o5b_h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="fgv34el5t"/><path class="nsl4o5b_h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:file-generic-fill-20" {...props}></Icon>
