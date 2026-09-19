<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/q6yn8gb3f.css';
import '../../css/i/ipg66nb4h.css';
import '../../css/s/syqz6bc1j.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="q6yn8gb3f"/><path class="ipg66nb4h"/><path class="syqz6bc1j"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:deciduoustree" {...props}></Icon>
