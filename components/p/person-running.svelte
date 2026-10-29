<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cogyhpbeg.css';
import '../../css/f/fa6cet7bu.css';
import '../../css/v/vvehkvu_h.css';
import '../../css/x/x_g42obzo.css';
import '../../css/q/qt9lwjbfz.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="cogyhpbeg wm-k"/><path class="fa6cet7bu wm-k"/><path class="vvehkvu_h wm-a"/><path class="wm-k x_g42obzo"/><path class="qt9lwjbfz wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:person-running" {...props}></Icon>
