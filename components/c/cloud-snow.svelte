<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/l12p6vo3k.css';
import '../../css/q/qqmov0t5w.css';
import '../../css/b/b8dal4kiv.css';
import '../../css/l/lztolrbic.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="l12p6vo3k wm-k"/><path class="qqmov0t5w wm-k"/><path class="b8dal4kiv wm-a"/><path class="lztolrbic wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:cloud-snow" {...props}></Icon>
