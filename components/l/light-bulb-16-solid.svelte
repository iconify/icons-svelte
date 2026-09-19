<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tomu-wbul.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="tomu-wbul"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:light-bulb-16-solid" {...props}></Icon>
