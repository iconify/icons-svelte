<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/h/hnsc5ccym.css';
import '../../css/p/p9vjoqtlo.css';
import '../../css/v/v0dnq2b7o.css';
import '../../css/f/fxwnb7vgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hnsc5ccym"/><circle class="p9vjoqtlo"/><circle class="p9vjoqtlo"/><circle class="v0dnq2b7o"/><circle class="fxwnb7vgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="majesticons:radio-list-line" {...props}></Icon>
