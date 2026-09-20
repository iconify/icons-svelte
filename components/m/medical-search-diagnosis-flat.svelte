<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/l/lwyw3okfs.css';
import '../../css/k/kalv0rbvz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="lwyw3okfs"/><path clip-rule="evenodd" class="kalv0rbvz"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:medical-search-diagnosis-flat" {...props}></Icon>
