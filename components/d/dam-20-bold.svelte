<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/i2x88vmhw.css';
import '../../css/p/pv9k0lrqk.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="i2x88vmhw"/><path class="pv9k0lrqk"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:dam-20-bold" {...props}></Icon>
