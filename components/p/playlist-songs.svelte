<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/l/l0_krduls.css';
import '../../css/g/gm3gd4twf.css';
import '../../css/o/ota-304ni.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="l0_krduls"/><path class="gm3gd4twf"/><path class="ota-304ni"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-ultimate:playlist-songs" {...props}></Icon>
