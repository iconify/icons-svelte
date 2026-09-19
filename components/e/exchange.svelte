<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y05ccfbwe.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1792,"height":1376};
const content = `<path class="y05ccfbwe"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="fa:exchange" {...props}></Icon>
