<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sj7dvbcbq.css';
import '../../css/t/tnw5n4brt.css';
import '../../css/d/deaxs3sre.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="sj7dvbcbq wm-k"/><path class="tnw5n4brt wm-a"/><path class="deaxs3sre wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:log-out" {...props}></Icon>
