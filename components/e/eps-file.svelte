<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qr3giu5xn.css';
import '../../css/c/ca34baqxh.css';
import '../../css/l/l56nfhv6e.css';
import '../../css/w/wwhv9711a.css';
import '../../css/b/b0cmkdksn.css';
import '../../css/b/bxqj37btp.css';
import '../../css/s/sewtzbcfr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":73,"height":88};
const content = `<path class="qr3giu5xn"/><path class="ca34baqxh"/><path class="l56nfhv6e"/><circle class="wwhv9711a"/><circle class="b0cmkdksn"/><circle class="bxqj37btp"/><path class="sewtzbcfr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:eps-file" {...props}></Icon>
