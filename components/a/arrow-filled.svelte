<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cuyn6tgcc.css';
import '../../css/l/l_jp68bwx.css';
import '../../css/u/ui8pwhfnc.css';
import '../../css/i/i392j1bbq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="l_jp68bwx"/><path class="ui8pwhfnc"/><path class="i392j1bbq"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="reicon:arrow-filled" {...props}></Icon>
