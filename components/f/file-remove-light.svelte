<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/t/th5uzgbxt.css';
import '../../css/d/dcnuadlyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="th5uzgbxt"/><path class="dcnuadlyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-remove-light" {...props}></Icon>
