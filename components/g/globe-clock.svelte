<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/frd8jk2_u.css';
import '../../css/i/igpa2gbno.css';
import '../../css/c/c_63rybwj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="frd8jk2_u"/><path class="igpa2gbno"/><circle class="c_63rybwj"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:globe-clock" {...props}></Icon>
