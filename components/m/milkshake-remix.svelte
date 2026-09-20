<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kc-a7d1cl.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="kc-a7d1cl"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline:milkshake-remix" {...props}></Icon>
