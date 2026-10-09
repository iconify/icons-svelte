<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rfao_6b1t.css';
import '../../css/c/c00kytlfm.css';
import '../../css/k/ka9ab8bek.css';
import '../../css/h/hss0ro0-v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<path class="rfao_6b1t"/><path class="c00kytlfm"/><path class="ka9ab8bek"/><path class="hss0ro0-v"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:electric-tractor-48-bold" {...props}></Icon>
