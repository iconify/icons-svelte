<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pj8wlmhgm.css';
import '../../css/x/xpk_g7bnh.css';
import '../../css/w/wgy-zbb8d.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pj8wlmhgm"/><path class="xpk_g7bnh"/><path class="wgy-zbb8d"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="gcp:dataprep" {...props}></Icon>
