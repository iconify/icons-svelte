<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/ft5dv1b6b.css';
import '../../css/g/gmwsuuafu.css';
import '../../css/i/idioxzbvi.css';
import '../../css/r/rqxdjtb9e.css';
import '../../css/w/w49j0rbvv.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<defs><mask id="SVGBcAkBbbn"><g class="ft5dv1b6b"><path class="gmwsuuafu"/><path class="idioxzbvi"/><path class="rqxdjtb9e"/></g></mask></defs><path mask="url(#SVGBcAkBbbn)" class="w49j0rbvv"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="lets-icons:compass-north-duotone" {...props}></Icon>
