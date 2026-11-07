<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/p/pi6xz2b_n.css';
import '../../css/d/dtoolxbmj.css';
import '../../css/n/nvxxmxb7r.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="pi6xz2b_n"/><path class="dtoolxbmj"/><path class="nvxxmxb7r"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:link-minimalistic-2-line-duotone" {...props}></Icon>
