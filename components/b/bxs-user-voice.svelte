<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gzuusgytb.css';
import '../../css/t/t_wx_r-8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gzuusgytb"/><path class="t_wx_r-8q"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bx:bxs-user-voice" {...props}></Icon>
