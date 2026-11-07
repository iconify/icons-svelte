<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xtpeb-edw.css';
import '../../css/l/l4sq9d0tz.css';
import '../../css/x/xr94vgbux.css';
import '../../css/m/m86y5nxtn.css';
import '../../css/f/f-ijm0bse.css';
import '../../css/h/hz0v1zbiu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="xtpeb-edw"><path class="l4sq9d0tz"/><path class="xr94vgbux"/><path class="m86y5nxtn"/><path class="f-ijm0bse"/></g><path class="hz0v1zbiu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="solar:list-plus-bold-duotone" {...props}></Icon>
