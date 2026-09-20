<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/v/vgdrhu2qc.css';
import '../../css/e/eetq4kbnf.css';
import '../../css/n/ney5_b6pk.css';
import '../../css/b/buo1kubox.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="vgdrhu2qc"/><path class="eetq4kbnf"/><path class="ney5_b6pk"/><path class="buo1kubox"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:bag-music-broken" {...props}></Icon>
