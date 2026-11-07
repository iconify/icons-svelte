<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/d/dnl23qbfb.css';
import '../../css/z/ze1h1pq4k.css';
import '../../css/p/p_ls0_vsw.css';
import '../../css/r/rbsce_beo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="dnl23qbfb"/><path class="ze1h1pq4k"/><path class="p_ls0_vsw"/><path class="rbsce_beo"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:notes-broken" {...props}></Icon>
