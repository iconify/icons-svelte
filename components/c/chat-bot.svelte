<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/q/qz4qdib_b.css';
import '../../css/r/r4f-rbb3p.css';
import '../../css/v/vo1c2hb_n.css';
import '../../css/v/vyei62k9q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="qz4qdib_b"/><path class="r4f-rbb3p"/><path class="vo1c2hb_n"/><path class="vyei62k9q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:chat-bot" {...props}></Icon>
