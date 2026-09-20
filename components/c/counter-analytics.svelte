<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j14ur1b8a.css';
import '../../css/y/ybf22hb-b.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="j14ur1b8a"/><path class="ybf22hb-b"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="selfhst:counter-analytics" {...props}></Icon>
