<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/s/shcvw7bpa.css';
import '../../css/e/ejb7eacvb.css';
import '../../css/v/v41ir48ee.css';
import '../../css/k/kqwl-3bjd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="shcvw7bpa"/><path class="ejb7eacvb wm-a"/><path class="v41ir48ee wm-k"/><path class="kqwl-3bjd wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:laugh-sketch" {...props}></Icon>
