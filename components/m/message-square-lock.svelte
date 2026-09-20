<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/nrj6p8qat.css';
import '../../css/e/eu8vrib5p.css';
import '../../css/w/wslrsl6lx.css';
import '../../css/b/bh4r24j1q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eu8vrib5p"/><path class="wslrsl6lx"/><rect class="bh4r24j1q"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide:message-square-lock" {...props}></Icon>
