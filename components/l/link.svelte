<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/zd12_wbjy.css';
import '../../css/i/iyp56ebds.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="zd12_wbjy"/><path class="iyp56ebds"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="icomoon-free:link" {...props}></Icon>
