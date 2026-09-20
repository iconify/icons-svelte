<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/kkf7gnbzc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":8,"height":8};
const content = `<path class="kkf7gnbzc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="picon:gsm4" {...props}></Icon>
