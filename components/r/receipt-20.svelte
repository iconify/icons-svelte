<script>
import Icon from '@iconify/css-svelte';
import '../../css/p/pepcxkbtl.css';
import '../../css/m/mvmh7mwai.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="pepcxkbtl"/><path class="mvmh7mwai"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="energy-icons:receipt-20" {...props}></Icon>
