<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/r/r83_z9bkg.css';
import '../../css/b/bser5vtcv.css';
import '../../css/f/fxwnb7vgp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="r83_z9bkg"/><circle class="bser5vtcv"/><circle class="fxwnb7vgp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:forklift" {...props}></Icon>
