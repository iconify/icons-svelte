<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pp140swdp.css';
import '../../css/l/lp2l3fbnm.css';
import '../../css/h/hguy1jb9d.css';
import '../../css/c/cy6059bvk.css';
import '../../css/p/phqtmmyeb.css';
import '../../css/t/ti49w-b1a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="pp140swdp"/><path class="lp2l3fbnm"/><path class="hguy1jb9d"/><path class="cy6059bvk"/><path class="phqtmmyeb"/><path class="ti49w-b1a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:cryptomator" {...props}></Icon>
