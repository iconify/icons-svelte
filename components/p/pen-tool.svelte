<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sv7ay2bxn.css';
import '../../css/l/lryctbccs.css';
import '../../css/i/iv7ukhb8n.css';
import '../../css/x/xxutnhb6o.css';
import '../../css/x/xwvuugy7n.css';
import '../../css/s/s_aaoy9gm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="sv7ay2bxn"><path class="lryctbccs wm-shadow"/><path class="iv7ukhb8n wm-shadow"/><path class="xxutnhb6o"/><path class="xwvuugy7n"/><path class="s_aaoy9gm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-brutal:pen-tool" {...props}></Icon>
