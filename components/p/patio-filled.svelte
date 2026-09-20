<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pfo1tsbjl.css';
import '../../css/p/pz67xgbrp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="pfo1tsbjl"/><path class="pz67xgbrp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:patio-filled" {...props}></Icon>
