<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/gmunasb2f.css';
import '../../css/x/xtpeb-edw.css';
import '../../css/e/e4fplvyta.css';
import '../../css/m/mfcab4xzh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<path class="gmunasb2f"/><g class="xtpeb-edw"><path clip-rule="evenodd" class="e4fplvyta"/><path class="mfcab4xzh"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="stash:calendar-end-duotone" {...props}></Icon>
