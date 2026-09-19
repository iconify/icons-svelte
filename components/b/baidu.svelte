<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/ngl4_3bgm.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":432,"height":488};
const content = `<path class="ngl4_3bgm"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="ps:baidu" {...props}></Icon>
