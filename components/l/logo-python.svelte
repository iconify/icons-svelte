<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sf7q6ji8c.css';
import '../../css/f/fvnxa3bsu.css';
import '../../css/m/mi_58-bbi.css';
import '../../css/l/leai81bxp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="sf7q6ji8c"/><path class="fvnxa3bsu"/><path class="mi_58-bbi"/><path class="leai81bxp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:logo-python" {...props}></Icon>
