<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/o/oc0vi5bvd.css';
import '../../css/y/y-h7hdc4i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="oc0vi5bvd"/><path class="y-h7hdc4i"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconamoon:location-pin-off-light" {...props}></Icon>
