<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/z/zlf7r1kic.css';
import '../../css/s/sicbtiqev.css';
import '../../css/m/mrcf2ubsb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zlf7r1kic"/><rect class="sicbtiqev"/><path class="mrcf2ubsb"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-lab:copy-file-path" {...props}></Icon>
