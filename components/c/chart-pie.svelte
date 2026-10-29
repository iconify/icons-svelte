<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fm66mfb8k.css';
import '../../css/k/k7rdutbey.css';
import '../../css/d/d1vzate5o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="fm66mfb8k wm-k"/><path class="k7rdutbey wm-k"/><path class="d1vzate5o wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:chart-pie" {...props}></Icon>
