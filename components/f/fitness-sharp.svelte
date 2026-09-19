<script>
import Icon from '@iconify/css-svelte';
import '../../css/d/d7k5gibth.css';
import '../../css/k/kjznt1r2d.css';
import '../../css/o/o-y2m3oef.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":512,"height":512};
const content = `<path class="d7k5gibth"/><path class="kjznt1r2d"/><path class="o-y2m3oef"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="famicons:fitness-sharp" {...props}></Icon>
