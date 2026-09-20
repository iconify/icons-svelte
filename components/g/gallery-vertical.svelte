<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/g/gtklzcyuo.css';
import '../../css/n/nz26t1bjz.css';
import '../../css/e/e4mo_8b_s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="gtklzcyuo"/><rect class="nz26t1bjz"/><path class="e4mo_8b_s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:gallery-vertical" {...props}></Icon>
