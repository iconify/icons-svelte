<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k470z5bpj.css';
import '../../css/y/y6r5hibqf.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="k470z5bpj"/><path class="y6r5hibqf"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lightbulb-sparkle-20-bold" {...props}></Icon>
