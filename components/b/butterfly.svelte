<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lcdcp95yn.css';
import '../../css/e/ek49ispnp.css';
import '../../css/b/bpw454b8q.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="lcdcp95yn wm-k"/><path class="ek49ispnp wm-k"/><path class="bpw454b8q wm-a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons-bauhaus:butterfly" {...props}></Icon>
