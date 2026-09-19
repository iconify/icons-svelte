<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qcpw2q4gb.css';
import '../../css/a/abq2l722c.css';
import '../../css/l/l10h6ebue.css';
import '../../css/v/vvlkjabbs.css';
import '../../css/m/myp7udbnu.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qcpw2q4gb"/><path class="abq2l722c"/><path class="l10h6ebue"/><circle class="vvlkjabbs"/><path class="myp7udbnu"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fxemoji:moviecamera" {...props}></Icon>
