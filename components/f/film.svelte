<script>
import Icon from '@iconify/css-svelte';
import '../../css/j/jdu8ew18m.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1025,"height":960};
const content = `<path class="jdu8ew18m"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:film" {...props}></Icon>
