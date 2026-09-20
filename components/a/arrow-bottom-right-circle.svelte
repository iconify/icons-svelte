<script>
import Icon from '@iconify/css-svelte';
import '../../css/w/w2o0yeblr.css';

/** @type {{width?: string; height?: string;}} */
let {width, height, ...props} = $props();

const viewBox = {"width":22,"height":22};
const content = `<path class="w2o0yeblr"/>`;
</script>
<Icon width={width} height={height} viewBox={viewBox} content={content} fallback="memory:arrow-bottom-right-circle" {...props}></Icon>
