<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wd1nwx7pc.css';
import '../../css/b/bp0flui-u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="wd1nwx7pc"/><path class="bp0flui-u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cil:bar-chart" {...props}></Icon>
