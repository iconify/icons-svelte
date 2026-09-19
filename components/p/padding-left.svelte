<script>
import Icon from '@iconify/css-svelte';
import '../../css/g/g1aphd7_t.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="g1aphd7_t"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:padding-left" {...props}></Icon>
