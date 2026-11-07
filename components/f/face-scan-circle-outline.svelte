<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hbp17eb1m.css';
import '../../css/x/xza96qbbg.css';
import '../../css/g/grj_h9ayp.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="hbp17eb1m"/><path class="xza96qbbg"/><path clip-rule="evenodd" class="grj_h9ayp"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:face-scan-circle-outline" {...props}></Icon>
