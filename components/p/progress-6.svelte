<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wv3cf2bwb.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1000,"height":1000};
const content = `<path class="wv3cf2bwb"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:progress-6" {...props}></Icon>
