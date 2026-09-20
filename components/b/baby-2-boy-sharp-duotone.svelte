<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/n/n77s3abja.css';
import '../../css/t/t11kj5rgv.css';
import '../../css/z/zbfc7cbxn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="n77s3abja"/><path class="t11kj5rgv"/><path class="zbfc7cbxn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:baby-2-boy-sharp-duotone" {...props}></Icon>
