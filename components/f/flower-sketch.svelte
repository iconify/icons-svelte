<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/x/xag6ozbqu.css';
import '../../css/r/r8hfrupfa.css';
import '../../css/s/sdb3vkbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="xag6ozbqu"/><path class="r8hfrupfa wm-k"/><path class="sdb3vkbhq wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:flower-sketch" {...props}></Icon>
