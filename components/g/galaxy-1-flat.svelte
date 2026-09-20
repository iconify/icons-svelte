<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/w/wc_cf_sdm.css';
import '../../css/g/g-8e__26p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<g class="ft5dv1b6b"><path class="wc_cf_sdm"/><path clip-rule="evenodd" class="g-8e__26p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-color:galaxy-1-flat" {...props}></Icon>
