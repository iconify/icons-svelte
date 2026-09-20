<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zlw4881-w.css';
import '../../css/f/fp5wvo1sn.css';
import '../../css/w/wwbd329qt.css';
import '../../css/h/hii85eizm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="zlw4881-w"/><path class="fp5wvo1sn"/><path class="wwbd329qt"/><path class="hii85eizm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:joomla" {...props}></Icon>
