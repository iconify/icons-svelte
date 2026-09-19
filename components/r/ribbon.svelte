<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mt8_63gik.css';
import '../../css/a/a2pc2urid.css';
import '../../css/q/qkkblme1u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="mt8_63gik"/><ellipse class="a2pc2urid"/><path class="qkkblme1u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:ribbon" {...props}></Icon>
