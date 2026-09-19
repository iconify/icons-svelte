<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/j_e59tbsr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="j_e59tbsr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:bug-solid" {...props}></Icon>
