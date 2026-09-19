<script>
import Icon from '@iconify/css-svelte';
import '../../css/y/y4kxfbcij.css';
import '../../css/s/sqhl82lfo.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":16,"height":16};
const content = `<path class="y4kxfbcij"/><path class="sqhl82lfo"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="heroicons:gift-top-16-solid" {...props}></Icon>
