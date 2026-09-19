<script>
import Icon from '@iconify/css-svelte';
import '../../css/h/ha1-zac3l.css';
import '../../css/d/d_11-9bwc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":32,"height":32};
const content = `<path class="ha1-zac3l"/><path class="d_11-9bwc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="carbon:radio" {...props}></Icon>
