<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dt0cm9dhy.css';
import '../../css/i/ij3vyybgh.css';
import '../../css/w/w3i1zx0jw.css';
import '../../css/q/qxjauly2w.css';
import '../../css/s/syoi7xbjn.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="dt0cm9dhy"><path class="ij3vyybgh"/><path class="w3i1zx0jw"/><path class="qxjauly2w"/><path class="syoi7xbjn"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="iconaut:pickup-truck" {...props}></Icon>
