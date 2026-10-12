<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/k/kc2n62g_e.css';
import '../../css/r/r7zp6bb5u.css';
import '../../css/e/emoy9fbht.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kc2n62g_e"/><path class="r7zp6bb5u"/><path class="emoy9fbht"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:clipboard-pen-duotone" {...props}></Icon>
