<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lbha9ecwq.css';
import '../../css/v/v67rwzb7l.css';
import '../../css/k/kw04ru5zn.css';
import '../../css/u/urmv84b7a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lbha9ecwq wm-shadow"/><path class="v67rwzb7l wm-shadow"/><path class="kw04ru5zn"/><path class="urmv84b7a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:gauge" {...props}></Icon>
