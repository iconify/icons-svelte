<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/t/t5su3hb9j.css';
import '../../css/l/lmh4whbrs.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<g class="nrj6p8qat"><path class="t5su3hb9j"/><circle class="lmh4whbrs"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bytesize:info" {...props}></Icon>
