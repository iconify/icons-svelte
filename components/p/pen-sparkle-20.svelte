<script>
import Icon from '@iconify/css-svelte';
import '../../css/z/z3320-d5h.css';
import '../../css/m/mt6c1q4zg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="z3320-d5h"/><path class="mt6c1q4zg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:pen-sparkle-20" {...props}></Icon>
