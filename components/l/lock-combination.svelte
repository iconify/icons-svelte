<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dwi2mlprc.css';
import '../../css/m/mp-hme0is.css';
import '../../css/k/kozuxzbrc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="dwi2mlprc"/><path class="mp-hme0is"/><circle class="kozuxzbrc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ion:lock-combination" {...props}></Icon>
