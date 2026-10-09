<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/prrieubjn.css';
import '../../css/o/o1dca9b1x.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="prrieubjn"/><path class="o1dca9b1x"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:lock-20" {...props}></Icon>
