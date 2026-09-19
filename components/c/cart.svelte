<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/m/mr9mvfbsp.css';
import '../../css/i/incllrbwl.css';
import '../../css/e/e2lc3dbws.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="nrj6p8qat"><path class="mr9mvfbsp"/><circle class="incllrbwl"/><circle class="e2lc3dbws"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:cart" {...props}></Icon>
