<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/h/hxo2p_vlt.css';
import '../../css/x/xknbt5ism.css';
import '../../css/a/ak7meacck.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="hxo2p_vlt"/><path class="xknbt5ism"/><path class="ak7meacck"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:inbox-check" {...props}></Icon>
