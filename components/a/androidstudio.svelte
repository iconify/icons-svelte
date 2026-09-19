<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jy2-3ytlx.css';
import '../../css/s/st8yw5ywg.css';
import '../../css/x/xyrv0gjyl.css';
import '../../css/h/h3ktuxbpl.css';
import '../../css/m/m1qi78b-s.css';
import '../../css/f/fg77xbckx.css';
import '../../css/w/wqxk8wvem.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":128,"height":128};
const content = `<path class="jy2-3ytlx"/><path class="st8yw5ywg"/><path class="xyrv0gjyl"/><path class="h3ktuxbpl"/><path class="m1qi78b-s"/><path class="fg77xbckx"/><path class="wqxk8wvem"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="devicon:androidstudio" {...props}></Icon>
