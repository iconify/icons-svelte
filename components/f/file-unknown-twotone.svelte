<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r1h2ywb3p.css';
import '../../css/z/z4pv5t1oe.css';
import '../../css/u/ub1afpn4a.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="r1h2ywb3p"/><path class="z4pv5t1oe"/><path class="ub1afpn4a"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ant-design:file-unknown-twotone" {...props}></Icon>
