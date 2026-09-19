<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/t-v7pcchz.css';
import '../../css/j/j-g4lup5t.css';
import '../../css/m/m7z06s_0u.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="t-v7pcchz"/><path class="j-g4lup5t"/><path class="m7z06s_0u"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="flag:am-1x1" {...props}></Icon>
