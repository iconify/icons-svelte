<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/o6g5v731f.css';
import '../../css/w/wdu67f6zs.css';
import '../../css/j/j829ogbst.css';
import '../../css/y/y47cdmcvq.css';
import '../../css/b/bbjw-ccll.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="o6g5v731f wm-a"/><path class="wdu67f6zs wm-k"/><path class="j829ogbst wm-a"/><path class="wm-a y47cdmcvq"/><path class="bbjw-ccll wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:radio" {...props}></Icon>
