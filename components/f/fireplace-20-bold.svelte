<script>
import Icon from '@iconify/css-svelte';
import '../../css/o/olltwdbuj.css';
import '../../css/f/flvfxybjw.css';
import '../../css/x/xw6i8dp-o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="olltwdbuj"/><path class="flvfxybjw"/><path class="xw6i8dp-o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fireplace-20-bold" {...props}></Icon>
