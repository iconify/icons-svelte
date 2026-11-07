<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/azy1lpbdu.css';
import '../../css/x/xwsg8i03s.css';
import '../../css/k/knfcb1bra.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="azy1lpbdu"/><path class="xwsg8i03s"/><path class="knfcb1bra"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:planet-3-bold-duotone" {...props}></Icon>
