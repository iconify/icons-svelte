<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/f/flbl44beh.css';
import '../../css/y/yp_dyqbmy.css';
import '../../css/i/igksilbgd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="flbl44beh"/><path class="wm-k yp_dyqbmy"/><path class="igksilbgd wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:picture-in-picture-sketch" {...props}></Icon>
