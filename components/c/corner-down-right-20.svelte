<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tbx9m__qq.css';
import '../../css/b/bj40tef2x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tbx9m__qq"/><path class="bj40tef2x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:corner-down-right-20" {...props}></Icon>
