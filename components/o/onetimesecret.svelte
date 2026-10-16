<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v22tdl34m.css';
import '../../css/x/xn2g6_jxx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<rect class="v22tdl34m"/><path class="xn2g6_jxx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="thesvg-color:onetimesecret" {...props}></Icon>
