<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/o/olt90gbii.css';
import '../../css/m/mkb_cm8ba.css';
import '../../css/n/ngupifb1v.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="olt90gbii"/><path class="mkb_cm8ba"/><path class="ngupifb1v"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="tdesign:chart-ring-1" {...props}></Icon>
