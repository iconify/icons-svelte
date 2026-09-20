<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/p/pxhl7lpbj.css';
import '../../css/y/yhnin7b0y.css';
import '../../css/b/bix9qiwrn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pxhl7lpbj"/><path class="yhnin7b0y"/><path class="bix9qiwrn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:brand-storj" {...props}></Icon>
