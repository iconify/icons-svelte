<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tczw_hbsg.css';
import '../../css/m/mnbdjobol.css';
import '../../css/p/pob-507pd.css';
import '../../css/y/yt4nl8b6h.css';
import '../../css/t/tlrdff70f.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":24,"height":24};
const content = `<g class="tczw_hbsg"><path class="mnbdjobol"/><path class="pob-507pd wm-a"/><path class="wm-k yt4nl8b6h"/><path class="tlrdff70f wm-a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="withicons:circle-dollar-sign-sketch" {...props}></Icon>
