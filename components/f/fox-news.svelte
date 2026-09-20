<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/dv26cacrn.css';
import '../../css/t/tn13mns0i.css';
import '../../css/m/mdz63-bin.css';
import '../../css/e/eh0vm5bms.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1235,"height":1235};
const content = `<path class="dv26cacrn"/><path class="tn13mns0i"/><path class="mdz63-bin"/><path class="eh0vm5bms"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:fox-news" {...props}></Icon>
