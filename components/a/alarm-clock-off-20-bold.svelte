<script>
import Icon from '@iconify/css-svelte';
import '../../css/a/asornzyio.css';
import '../../css/e/elstku5yi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="asornzyio"/><path class="elstku5yi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:alarm-clock-off-20-bold" {...props}></Icon>
