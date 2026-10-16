<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iwcpavbfl.css';
import '../../css/v/vcbhgbcuw.css';
import '../../css/r/r9oealbdj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iwcpavbfl"/><path class="vcbhgbcuw"/><path class="r9oealbdj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:hydrogen-ship-20-bold" {...props}></Icon>
