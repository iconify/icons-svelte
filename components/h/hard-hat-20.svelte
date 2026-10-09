<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z4yi2x4py.css';
import '../../css/u/uax5j8b6w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z4yi2x4py"/><path class="uax5j8b6w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hard-hat-20" {...props}></Icon>
