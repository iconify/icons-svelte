<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/owfg3hrsx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="owfg3hrsx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:peak-demand-20-bold" {...props}></Icon>
