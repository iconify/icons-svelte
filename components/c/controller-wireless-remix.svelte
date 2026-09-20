<script>
import Icon from '@iconify/css-svelte';
import '../../css/m/mey8kkb6h.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":14,"height":14};
const content = `<path clip-rule="evenodd" class="mey8kkb6h"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="streamline-flex:controller-wireless-remix" {...props}></Icon>
