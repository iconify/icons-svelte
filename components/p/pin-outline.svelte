<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xbncc194d.css';
import '../../css/r/rnfj33zxy.css';
import '../../css/x/xpiiaw94l.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":15,"height":15};
const content = `<g clip-rule="evenodd" class="xbncc194d"><path class="rnfj33zxy"/><path class="xpiiaw94l"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="teenyicons:pin-outline" {...props}></Icon>
