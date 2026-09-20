<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/a/a5ps5fbpe.css';
import '../../css/v/vo2em-b5e.css';
import '../../css/v/vo4tnbc2j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="a5ps5fbpe"/><rect class="vo2em-b5e"/><path class="vo4tnbc2j"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:car-front" {...props}></Icon>
