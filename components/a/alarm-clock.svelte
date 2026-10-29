<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z9ttgzwoy.css';
import '../../css/a/a9r0l3bpj.css';
import '../../css/p/pq5d4i-df.css';
import '../../css/c/csl8dlbrs.css';
import '../../css/r/rjunq3ykp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="wm-a z9ttgzwoy"/><path class="a9r0l3bpj wm-a"/><path class="pq5d4i-df wm-k"/><path class="csl8dlbrs wm-k"/><path class="rjunq3ykp wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:alarm-clock" {...props}></Icon>
