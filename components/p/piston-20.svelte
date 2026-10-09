<script>
import Icon from '@iconify/css-svelte';
import '../../css/x/xjnxpnb1o.css';
import '../../css/d/dk6kerbsg.css';
import '../../css/b/be65o352o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="xjnxpnb1o"/><path class="dk6kerbsg"/><path class="be65o352o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:piston-20" {...props}></Icon>
