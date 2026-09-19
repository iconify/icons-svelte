<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/r3oc3o71y.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path clip-rule="evenodd" class="r3oc3o71y"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:arrow-turn-right-down-16-solid" {...props}></Icon>
