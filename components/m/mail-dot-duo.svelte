<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/h9ibb1b7a.css';
import '../../css/d/dt0cm9dhy.css';
import '../../css/k/kfa274xjb.css';
import '../../css/l/lfcrxhbkr.css';
import '../../css/x/xd8yd0bhm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="h9ibb1b7a secondary"/><g class="dt0cm9dhy primary"><path class="kfa274xjb"/><path class="lfcrxhbkr"/><path class="xd8yd0bhm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:mail-dot-duo" {...props}></Icon>
