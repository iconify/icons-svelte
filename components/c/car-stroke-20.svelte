<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tem_62y7z.css';
import '../../css/y/yx0hc3b0s.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="tem_62y7z"/><path class="yx0hc3b0s"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="garden:car-stroke-20" {...props}></Icon>
