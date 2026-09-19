<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/u2sryobdh.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":857,"height":1000};
const content = `<path class="u2sryobdh"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="websymbol:arrows-cw" {...props}></Icon>
