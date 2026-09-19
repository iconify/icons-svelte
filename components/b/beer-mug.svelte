<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v3_i3wktz.css';
import '../../css/p/p2xwiqh_v.css';
import '../../css/x/xzxsc8bqh.css';
import '../../css/t/tvpmmp2in.css';
import '../../css/b/bl95smbeo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":48,"height":48};
const content = `<defs><mask id="SVGOUJQzbCo"><g class="v3_i3wktz"><path class="p2xwiqh_v"/><path class="xzxsc8bqh"/><path class="tvpmmp2in"/></g></mask></defs><path mask="url(#SVGOUJQzbCo)" class="bl95smbeo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icon-park-twotone:beer-mug" {...props}></Icon>
