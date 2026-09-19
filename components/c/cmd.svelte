<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rq367fyro.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":1024};
const content = `<path class="rq367fyro"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:cmd" {...props}></Icon>
