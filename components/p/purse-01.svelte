<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/b/bujqc9bzy.css';
import '../../css/o/oa9vxvzug.css';
import '../../css/o/olphuzb2n.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bujqc9bzy"/><path class="oa9vxvzug"/><path class="olphuzb2n"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:purse-01" {...props}></Icon>
