<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/m/ml60ou10h.css';
import '../../css/e/eyjdl3b6j.css';
import '../../css/f/fru9xgbyt.css';
import '../../css/p/puy2ak-rd.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path clip-rule="evenodd" class="ml60ou10h"/><path clip-rule="evenodd" class="eyjdl3b6j"/><path class="fru9xgbyt"/><path class="puy2ak-rd"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-sharp-color:drone-flat" {...props}></Icon>
