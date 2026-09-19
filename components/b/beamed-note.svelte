<script>
import Icon from '@iconify/css-svelte';
import '../../css/c/cmkh4p2mx.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":20,"height":20};
const content = `<path class="cmkh4p2mx"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="entypo:beamed-note" {...props}></Icon>
