<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iixfqsbra.css';
import '../../css/u/upuxwyb9o.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="iixfqsbra"/><path class="upuxwyb9o"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:fuel-pump-20" {...props}></Icon>
