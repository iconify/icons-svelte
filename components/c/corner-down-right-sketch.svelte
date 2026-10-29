<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/q/qz-wqrb_o.css';
import '../../css/b/bo8a-d58q.css';
import '../../css/o/ofugmqbjy.css';
import '../../css/l/l2g7ifo6y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="qz-wqrb_o wm-k"/><path class="bo8a-d58q wm-a"/><path class="ofugmqbjy wm-k"/><path class="l2g7ifo6y wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:corner-down-right-sketch" {...props}></Icon>
