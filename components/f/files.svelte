<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/a/atdeesb2k.css';
import '../../css/l/lpbxz5bsk.css';
import '../../css/s/sizmydbvw.css';
import '../../css/p/p_g5enbde.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="atdeesb2k wm-shadow"/><path class="lpbxz5bsk wm-shadow"/><path class="sizmydbvw"/><path class="p_g5enbde"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:files" {...props}></Icon>
