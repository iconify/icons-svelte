<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/wkazs2b4g.css';
import '../../css/r/rms53rbhq.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="wkazs2b4g"/><path class="rms53rbhq"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:apple" {...props}></Icon>
