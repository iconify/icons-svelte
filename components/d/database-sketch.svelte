<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/p/p8k8z9eib.css';
import '../../css/i/ie52vmbhx.css';
import '../../css/t/t7rl4acgf.css';
import '../../css/n/n7avn2bad.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="p8k8z9eib"/><path class="ie52vmbhx wm-a"/><path class="t7rl4acgf wm-k"/><path class="n7avn2bad wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:database-sketch" {...props}></Icon>
