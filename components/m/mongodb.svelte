<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/hzr_vydyg.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="hzr_vydyg"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="cib:mongodb" {...props}></Icon>
