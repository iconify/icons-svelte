<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/v/vepjdob9n.css';
import '../../css/w/wc49swbmj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="nrj6p8qat"><path class="vepjdob9n"/><circle class="wc49swbmj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:photo" {...props}></Icon>
