<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y7qa5lbsc.css';
import '../../css/u/uz-tkbbqf.css';
import '../../css/l/lruh5mb8n.css';
import '../../css/o/oa3hoyr8p.css';
import '../../css/r/rbls-1btg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="y7qa5lbsc"/><path clip-rule="evenodd" class="uz-tkbbqf"/><path class="lruh5mb8n"/><path class="oa3hoyr8p"/><path class="rbls-1btg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="token:cap" {...props}></Icon>
