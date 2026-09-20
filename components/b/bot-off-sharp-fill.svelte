<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gp_8x1bzb.css';
import '../../css/w/wel3ij-ab.css';
import '../../css/u/ur0kqubed.css';
import '../../css/s/sp3ujwwyq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path clip-rule="evenodd" class="wel3ij-ab"/><path class="ur0kqubed"/><path class="sp3ujwwyq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="keyline-icons:bot-off-sharp-fill" {...props}></Icon>
