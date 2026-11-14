<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qloeeh4pd.css';
import '../../css/t/tw_5ixbdl.css';
import '../../css/c/c6dpzhafn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="qloeeh4pd"><path class="tw_5ixbdl"/><path class="c6dpzhafn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:bubble-chat-secure" {...props}></Icon>
