<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w_vulybfi.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="w_vulybfi"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:line-arrow-crossover-right-remix" {...props}></Icon>
