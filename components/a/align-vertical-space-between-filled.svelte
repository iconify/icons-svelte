<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wmes9zbiw.css';
import '../../css/h/homzn5bbs.css';
import '../../css/s/s6a_vl58s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wmes9zbiw"/><rect class="homzn5bbs"/><rect class="s6a_vl58s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="boxicons:align-vertical-space-between-filled" {...props}></Icon>
