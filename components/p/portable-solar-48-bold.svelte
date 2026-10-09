<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/akt-vlbtw.css';
import '../../css/l/lq07xlbfl.css';
import '../../css/h/hlva2pb_n.css';
import '../../css/e/ex_mzw_ak.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="akt-vlbtw"/><path class="lq07xlbfl"/><path class="hlva2pb_n"/><path class="ex_mzw_ak"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:portable-solar-48-bold" {...props}></Icon>
