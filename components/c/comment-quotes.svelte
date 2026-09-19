<script>
import Icon from '@iconify/css-svelte';
import '../../css/u/ubv9gybnc.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":100,"height":100};
const content = `<path class="ubv9gybnc"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="foundation:comment-quotes" {...props}></Icon>
