<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jx0p4fbya.css';
import '../../css/g/gu0boielt.css';
import '../../css/r/roqcz1pae.css';
import '../../css/u/uztmj3dza.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="jx0p4fbya"><path class="gu0boielt"/><path class="roqcz1pae"/><path class="uztmj3dza"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="hugeicons:analytics-down" {...props}></Icon>
