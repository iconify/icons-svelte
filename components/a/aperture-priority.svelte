<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ufeehvblu.css';
import '../../css/g/g7c0sab9y.css';
import '../../css/n/n7whz5z0y.css';
import '../../css/e/eojrxsbwi.css';
import '../../css/p/pw7p7hvoa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="ufeehvblu"><path class="g7c0sab9y"/><path class="n7whz5z0y"/><path class="eojrxsbwi"/><path class="pw7p7hvoa"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park:aperture-priority" {...props}></Icon>
