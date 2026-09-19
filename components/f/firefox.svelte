<script>
import Icon from '@iconify/css-svelte';
import '../../css/r/rh516mbvj.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":1024,"height":1024};
const content = `<path class="rh516mbvj"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="whh:firefox" {...props}></Icon>
