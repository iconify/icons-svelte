<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/f/fj12aacni.css';
import '../../css/i/iqbjcwbwg.css';
import '../../css/v/v41nt6s4e.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fj12aacni"/><path class="iqbjcwbwg"/><path class="v41nt6s4e"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tabler:home-eco" {...props}></Icon>
