<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bi12bsetm.css';
import '../../css/v/vifru3bat.css';
import '../../css/k/kl7dgmbhv.css';
import '../../css/f/fk2z6voyg.css';
import '../../css/n/nqgr1cd4k.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g clip-rule="evenodd" class="bi12bsetm"><path class="vifru3bat"/><path class="kl7dgmbhv"/><path class="fk2z6voyg"/><path class="nqgr1cd4k"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex-color:image-location-flat" {...props}></Icon>
