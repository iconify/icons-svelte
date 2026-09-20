<script>
import Icon from '@iconify/css-svelte';
import '../../css/k/k5a6-gbto.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="k5a6-gbto"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:alpha-j" {...props}></Icon>
