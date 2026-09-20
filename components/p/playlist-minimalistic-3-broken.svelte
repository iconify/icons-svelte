<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/b/b8qhkbcan.css';
import '../../css/e/eayvs1m_n.css';
import '../../css/d/d_y_0lfcd.css';
import '../../css/s/srbmx6fzm.css';
import '../../css/k/kcbqm3ber.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="b8qhkbcan"/><path class="eayvs1m_n"/><path class="d_y_0lfcd"/><path class="srbmx6fzm"/><path class="kcbqm3ber"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:playlist-minimalistic-3-broken" {...props}></Icon>
