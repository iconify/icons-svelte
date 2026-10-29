<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/k/kr89-5bas.css';
import '../../css/e/epj0hxbqe.css';
import '../../css/w/w88g0g3vx.css';
import '../../css/i/i_kfu3tmd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="kr89-5bas"/><path class="epj0hxbqe wm-a"/><path class="w88g0g3vx wm-k"/><path class="i_kfu3tmd wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:candy-bucket-sketch" {...props}></Icon>
