<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/ipq1z-bjh.css';
import '../../css/w/wkem_ebde.css';
import '../../css/p/pk8hibb5s.css';
import '../../css/a/avc6w_f8t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wkem_ebde"/><path class="pk8hibb5s"/><path class="avc6w_f8t"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:mail-account-02" {...props}></Icon>
