<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/y/yp4f68blr.css';
import '../../css/v/vzyv8dwha.css';
import '../../css/y/y6e3kecwn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yp4f68blr"/><rect class="vzyv8dwha"/><path class="y6e3kecwn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:radio-receiver" {...props}></Icon>
