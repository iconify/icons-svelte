<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/w/wzu4c0bsi.css';
import '../../css/z/zf_z6v05p.css';
import '../../css/n/nqvv9lbxu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><circle class="wzu4c0bsi"/><circle class="zf_z6v05p"/><path class="nqvv9lbxu"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:music-02" {...props}></Icon>
