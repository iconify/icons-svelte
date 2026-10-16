<script>
import Icon from '@iconify/css-svelte';
import '../../css/e/eageplt4r.css';
import '../../css/s/sjlcjjhzm.css';
import '../../css/s/s044fpzgh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="eageplt4r"/><path class="sjlcjjhzm"/><path class="s044fpzgh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:charger-solar-20-bold" {...props}></Icon>
