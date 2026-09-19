<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/vjjreccxy.css';
import '../../css/t/t_s_xqb-n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path clip-rule="evenodd" class="vjjreccxy"/><path class="t_s_xqb-n"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="bitcoin-icons:drops-filled" {...props}></Icon>
