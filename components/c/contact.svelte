<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/ryjcjykdw.css';
import '../../css/r/riikknfdi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ryjcjykdw"/><path class="riikknfdi"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="vadivam:contact" {...props}></Icon>
