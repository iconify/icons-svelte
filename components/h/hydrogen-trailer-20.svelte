<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wxm1vbcze.css';
import '../../css/c/cdve484mo.css';
import '../../css/x/xwbticcgw.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wxm1vbcze"/><path class="cdve484mo"/><path class="xwbticcgw"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-trailer-20" {...props}></Icon>
