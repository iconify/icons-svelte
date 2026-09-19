<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mmcg5w62t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":640,"height":512};
const content = `<path class="mmcg5w62t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa6-regular:comments" {...props}></Icon>
