<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d2kvgvbvc.css';
import '../../css/o/oss8fvbse.css';
import '../../css/r/ry3d24byu.css';
import '../../css/m/msf1qbjnq.css';
import '../../css/f/fzlwwzbri.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="d2kvgvbvc"><path class="oss8fvbse"/><path class="ry3d24byu"/><path class="msf1qbjnq"/><path class="fzlwwzbri"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:avatar-teen" {...props}></Icon>
