<script>
import Icon from '@iconify/css-svelte';
import '../../css/l/ltsvmv17u.css';
import '../../css/p/pvoys4t1r.css';
import '../../css/n/nr1kobbpa.css';
import '../../css/r/rgdhmtlro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ltsvmv17u"/><path class="pvoys4t1r"/><path class="nr1kobbpa"/><path class="ouiIcon__fillSecondary rgdhmtlro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="oui:app-watches" {...props}></Icon>
