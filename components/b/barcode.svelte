<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hynd_kb9n.css';
import '../../css/n/ni0f_pbls.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="hynd_kb9n"/><path class="ni0f_pbls"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:barcode" {...props}></Icon>
