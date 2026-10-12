<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/m578dxb1e.css';
import '../../css/m/mlhz2kbie.css';
import '../../css/k/kocu-gbtd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="m578dxb1e"/><path class="mlhz2kbie"/><path class="kocu-gbtd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lucide-extended:lamp-desk-duotone" {...props}></Icon>
