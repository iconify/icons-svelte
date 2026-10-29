<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bxjl7h_2h.css';
import '../../css/p/puwnn8bma.css';
import '../../css/f/fsdyx0e6l.css';
import '../../css/y/ywhe_o_vn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bxjl7h_2h wm-k"/><path class="puwnn8bma wm-k"/><path class="fsdyx0e6l wm-a"/><path class="wm-k ywhe_o_vn"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:factory" {...props}></Icon>
