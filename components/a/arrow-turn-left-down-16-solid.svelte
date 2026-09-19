<script>
import Icon from '@iconify/css-svelte';
import '../../css/f/fxgm09bzy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="fxgm09bzy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-left-down-16-solid" {...props}></Icon>
