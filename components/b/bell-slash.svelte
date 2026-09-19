<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hntgybcog.css';
import '../../css/i/i-50d2biz.css';
import '../../css/s/sdp6-tbwn.css';
import '../../css/t/t4o8ctohm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<g class="hntgybcog"><path class="i-50d2biz"/><path class="sdp6-tbwn"/><path class="i-50d2biz"/><path class="t4o8ctohm"/></g>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="charm:bell-slash" {...props}></Icon>
