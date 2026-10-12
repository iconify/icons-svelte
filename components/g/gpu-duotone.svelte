<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/n/n3gj0l26m.css';
import '../../css/u/uejy3gf8k.css';
import '../../css/p/pi_2brphp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="n3gj0l26m"/><path class="uejy3gf8k"/><path clip-rule="evenodd" class="pi_2brphp"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:gpu-duotone" {...props}></Icon>
