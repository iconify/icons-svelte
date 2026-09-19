<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/s212d_bjy.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":2048,"height":2048};
const content = `<path class="s212d_bjy"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fluent-mdl2:browser-screen-shot" {...props}></Icon>
