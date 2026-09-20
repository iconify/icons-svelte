<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gjj4o5bfd.css';
import '../../css/q/q9l_p2d0k.css';
import '../../css/l/luprff94i.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gjj4o5bfd"/><path class="q9l_p2d0k"/><path class="luprff94i"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="uim:comment-message" {...props}></Icon>
