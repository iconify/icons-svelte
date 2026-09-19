<script>
import Icon from '@iconify/css-svelte';
import '../../css/q/qndo5pb1f.css';
import '../../css/g/gi1zq4blx.css';
import '../../css/d/doic5013b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="qndo5pb1f"/><path class="gi1zq4blx"/><path class="doic5013b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:cz-1x1" {...props}></Icon>
