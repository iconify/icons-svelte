<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hu-l-lbvx.css';
import '../../css/g/g0t4uwbww.css';
import '../../css/c/c7ecv3bfa.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="hu-l-lbvx"/><path class="g0t4uwbww"/><path class="c7ecv3bfa"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:energy-trading-20" {...props}></Icon>
