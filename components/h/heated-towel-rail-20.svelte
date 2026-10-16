<script>
import Icon from '@iconify/css-svelte';
import '../../css/n/n5u1h0b8u.css';
import '../../css/t/tn9n3kd1w.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="n5u1h0b8u"/><path class="tn9n3kd1w"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:heated-towel-rail-20" {...props}></Icon>
