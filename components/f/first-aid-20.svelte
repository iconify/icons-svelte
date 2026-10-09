<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/ywju0hn3b.css';
import '../../css/l/lytqpepod.css';
import '../../css/o/ortt9nb3x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="ywju0hn3b"/><path class="lytqpepod"/><path class="ortt9nb3x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:first-aid-20" {...props}></Icon>
