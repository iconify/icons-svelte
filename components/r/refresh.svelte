<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bc0i3r_es.css';
import '../../css/v/vd-a_tg_q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="bc0i3r_es"/><path class="vd-a_tg_q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:refresh" {...props}></Icon>
