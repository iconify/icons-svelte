<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xpk_r1xfw.css';
import '../../css/j/jwxrimbri.css';
import '../../css/r/rsw0cp66o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="xpk_r1xfw"/><path class="jwxrimbri"/><path class="rsw0cp66o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:processing" {...props}></Icon>
