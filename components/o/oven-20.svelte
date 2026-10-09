<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/ckdxm-8ru.css';
import '../../css/f/fhd5hqc9p.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ckdxm-8ru"/><path class="fhd5hqc9p"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:oven-20" {...props}></Icon>
