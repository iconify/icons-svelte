<script>
import Icon from '@iconify/css-svelte';
import '../../css/i/iuj8j_bro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="iuj8j_bro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:play" {...props}></Icon>
