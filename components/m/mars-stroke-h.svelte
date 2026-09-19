<script>
import Icon from '@iconify/css-svelte';
import '../../css/t/tplqalbyh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1920,"height":1280};
const content = `<path class="tplqalbyh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:mars-stroke-h" {...props}></Icon>
