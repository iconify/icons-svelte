<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/s/skurl8bms.css';
import '../../css/i/i22c82bof.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="nrj6p8qat"><path class="skurl8bms"/><path class="i22c82bof"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:creditcard" {...props}></Icon>
