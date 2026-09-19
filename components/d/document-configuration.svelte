<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/delp4wn8f.css';
import '../../css/n/n273d0b2g.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="delp4wn8f"/><path class="n273d0b2g"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:document-configuration" {...props}></Icon>
