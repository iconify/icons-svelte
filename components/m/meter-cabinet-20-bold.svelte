<script>
import Icon from '@iconify/css-svelte';
import '../../css/v/v0i_05b_b.css';
import '../../css/m/mp3j7pbyx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="v0i_05b_b"/><path class="mp3j7pbyx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:meter-cabinet-20-bold" {...props}></Icon>
