<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wo2_hufaw.css';
import '../../css/k/k4x3-0b4z.css';
import '../../css/f/f2fykithr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="wo2_hufaw"/><path class="k4x3-0b4z"/><path class="f2fykithr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:plant-20" {...props}></Icon>
