<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jtowsomii.css';
import '../../css/h/hvb_mgbxp.css';
import '../../css/o/owdwaw4ke.css';
import '../../css/f/f_qg2bg2p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":21,"height":21};
const content = `<g class="jtowsomii"><path class="hvb_mgbxp"/><path class="owdwaw4ke"/><path class="f_qg2bg2p"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="system-uicons:retweet" {...props}></Icon>
