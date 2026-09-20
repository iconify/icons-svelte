<script>
import Icon from '@iconify/css-svelte';
import '../../css/s/sqag7l0gr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="sqag7l0gr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="zondicons:battery-low" {...props}></Icon>
