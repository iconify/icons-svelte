<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hit3bi0-v.css';
import '../../css/l/l9up7cgwq.css';
import '../../css/t/tbtmy19aj.css';
import '../../css/x/x3o8e895h.css';
import '../../css/b/bl4gd2e5a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<g class="hit3bi0-v"><path class="l9up7cgwq"/><path class="tbtmy19aj"/><ellipse transform="rotate(-45 14 14)" class="x3o8e895h"/><ellipse transform="rotate(-45 38 38)" class="bl4gd2e5a"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-outline:goblet-one" {...props}></Icon>
