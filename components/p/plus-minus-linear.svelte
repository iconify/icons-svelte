<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/n/n4-leiwdt.css';
import '../../css/m/mnqjcr06i.css';
import '../../css/s/sazi09x4s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="n4-leiwdt"/><path class="mnqjcr06i"/><path class="sazi09x4s"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:plus-minus-linear" {...props}></Icon>
