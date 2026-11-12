<script>
import Icon from '@iconify/css-svelte';
import '../../css/b/bp-zmabdk.css';
import '../../css/x/xpcab6bil.css';
import '../../css/b/bubqg0bxl.css';
import '../../css/g/gehiu-baz.css';
import '../../css/a/av6swrb7n.css';
import '../../css/y/yppsxpbxw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="bp-zmabdk"/><path class="xpcab6bil"/><path class="bubqg0bxl"/><path class="gehiu-baz"/><path class="av6swrb7n"/><path class="yppsxpbxw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:kitsu-light" {...props}></Icon>
