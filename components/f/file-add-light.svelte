<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/ddvgu8bvv.css';
import '../../css/c/cnkqfptnp.css';
import '../../css/d/dcnuadlyf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ddvgu8bvv"><path class="cnkqfptnp"/><path class="dcnuadlyf"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:file-add-light" {...props}></Icon>
