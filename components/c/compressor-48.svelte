<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/lnw5nvftm.css';
import '../../css/q/q177d-m0y.css';
import '../../css/h/h7hp1q67c.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="lnw5nvftm"/><path class="q177d-m0y"/><path class="h7hp1q67c"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:compressor-48" {...props}></Icon>
